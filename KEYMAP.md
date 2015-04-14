File Management
---------------

  Open Keybindings file

  ```js
  {
    "keys": ["alt+super+,"],
    "command": "open_file",
    "args": { "file": "${packages}/User/Default (OSX).sublime-keymap" }
  }
  ```

  Rename file

  ```js
  {
    "keys": ["super+alt+ctrl+shift+r"],
    "command": "side_bar_rename"
  }
  ```


  ```js
  {
    "keys": ["super+alt+ctrl+shift+m"],
    "command": "side_bar_move"
  }
  ```

Limit cycling to group
----------------------

  Cycle views

  ```js
  {
    "keys": ["super+shift+["],
    "command": "prev_view_in_group"
  }
  ```


  ```js
  {
    "keys": ["super+shift+]"],
    "command": "next_view_in_group"
  }
  ```

Find
----

  Find and Replace in file by default

  ```js
  {
    "keys": ["super+f"],
    "command": "show_panel",
    "args": {"panel": "replace"}
  }
  ```

  Find and Replace in project by default

  ```js
  {
    "keys": ["super+shift+f"],
    "command": "show_panel",
    "args": {"panel": "find_in_files"}
  }
  ```

  Replace next match

  ```js
  {
    "keys": ["super+alt+f"],
    "command": "replace_next"
  }
  ```

  Find next match

  ```js
  {
    "keys": ["super+g"],
    "command": "find_next"
  }
  ```

  Find previous match

  ```js
  {
    "keys": ["super+shift+g"],
    "command": "find_prev"
  }
  ```

  ⌥⌘F Replace selection

  ```js
  {
    "keys": ["alt+super+f"],
    "command": "replace_next"
  }
  ```

  ⌘G Next match

  ```js
  {
    "keys": ["super+g"],
    "command": "find_next"
  }
  ```

  ⇧⌘G Previous match

  ```js
  {
    "keys": ["shift+super+g"],
    "command": "find_prev"
  }
  ```


Multiple Cursors
----------------

  ⌥⌘D Skip selection

  ```js
  {
    "keys": ["alt+super+d"],
    "command": "find_under_expand_skip"
  }
  ```

Text commands
-------------

  ⌘V Paste and indent by default

  ```js
  {
    "keys": ["super+v"],
    "command": "paste_and_indent"
  }
  ```

  F5 Sort lines

  ```js
  {
    "keys": ["f5"],
    "command": "sort_lines",
    "args": {"case_sensitive": false}
  }
  ```

Window Management
-----------------

  ⇧⌃⌥⌘W Close All windows

  ```js
  {
    "keys": ["shift+ctrl+alt+super+w"],
    "command": "close_all"
  }
  ```

  ⌃⌥⌘D Toggle Drawer

  ```js
  {
    "keys": ["ctrl+alt+super+d"],
    "command": "toggle_side_bar"
  }
  ```

  ⌃⌥⌘M Toggle Mini Map

  ```js
  {
    "keys": ["ctrl+alt+super+m"],
    "command": "toggle_minimap"
  }
  ```

  ⇧⌘T Reopen tab

  ```js
  {
    "keys": ["shift+super+t"],
    "command": "reopen_last_file"
  }
  ```

File Management
---------------

  ⌘N New file

  ```js
  {
    "keys": ["super+n"],
    "command": "advanced_new_file_new"},

  ⇧⌘M Open Latest Migration

  ```js
  {
    "keys": ["shift+super+m"],
    "command": "rails_latest_migration"},

  ⇧⌘F Find and Replace in Project

  ```js
  {
    "keys": ["shift+super+f"],
    "command": "show_panel",
    "args": {"panel": "find_in_files"}
  }
  ```

  ⌘F Find and Replace

  ```js
  {
    "keys": ["super+f"],
    "command": "show_panel",
    "args": {"panel": "replace"}
  }
  ```

  ⌃⌘R Show file in sidebar

  ```js
  {
    "keys": ["ctrl+super+r"],
    "command": "reveal_in_side_bar"
  }
  ```

  ⇧⌃⌘N New Scratchpad

  ```js
  {
    "keys": ["shift+ctrl+super+n"],
    "command": "scratchpad"
  }
  ```

Text case
---------

  ⌥⌘U Uppercase

  ```js
  {
    "keys": ["ctrl+alt+super+u"],
    "command": "upper_case"
  }
  ```

  ⌥⌘L Lowercase

  ```js
  {
    "keys": ["alt+super+l"],
    "command": "lower_case"
  }
  ```

  ⌃⌥⌘U Titlecase

  ```js
  {
    "keys": ["alt+super+u"],
    "command": "title_case"
  }
  ```

Text Insertion
-----------------

  ⌥⌘= Hash Rocket

  ```js
  {
    "keys": ["alt+super+="],
    "command": "insert_snippet",
    "args": {"contents": "=>"}
  }
  ```

  ⌥⌘` Spermy lock operator

  ```js
  {
    "keys": ["alt+super+`"],
    "command": "insert_snippet",
    "args": {"contents": "~>"}
  }
  ```

  ⌃0 Insert right parens

  ```js
  {
    "keys": ["ctrl+0"],
    "command": "insert_snippet",
    "args": {"contents": ")"}},

  ⌃9 Insert left parens

  ```js
  {
    "keys": ["ctrl+9"],
    "command": "insert_snippet",
    "args": {"contents": "("}
    }
  ```

  ⌃' Insert double quotes

  ```js
  {
    "keys": ["ctrl+'"],
    "command": "insert_snippet",
    "args": {"contents": "\""}
  }
  ```

  ⌥⌘- Stabby Arrow

  ```js
  {
    "keys": ["alt+super+-"],
    "command": "insert_snippet",
    "args": {"contents": "->"}
  }
  ```

  ⇧⌥⌘_ To Underscore

  ```js
  {
    "keys": ["shift+ctrl+-"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/sh-string-to-underline.sublime-snippet"}
  }
  ```

  ⌃⌥⌘= Convert Hash Rockets

  ```js
  {
    "keys": ["ctrl+alt+super+="],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-hash-convert.sublime-snippet"}
  }
  ```

  ⇧⌃: String to Symbol

  ```js
  {
    "keys": ["shift+ctrl+;"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-symbolize.sublime-snippet"}
  }
  ```

  ⇧⌘" Symbol to String

  ```js
  {
    "keys": ["shift+super+'"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-unsymbolize.sublime-snippet"}
  }
  ```

  ⌥⌘CColor picker

  ```js
  {
    "keys": ["alt+super+c"], "command": "color_pick"
  }
  ```

  ⌃; Add semicolon at end of line

  ```js
  {
    "keys": ["ctrl+;"],
    "command": "chain",
    "args": {
      "commands": [
        ["move_to", { "to": "eol" }],
        ["insert_snippet", {"contents": ";"}]
      ]
    }
  ```
  }
  ```

  ⌃= Add == at end of line

  ```js
  {
    "keys": ["ctrl+="],
    "command": "chain",
    "args": {
      "commands": [
        ["move_to", { "to": "eol" }],
        ["insert_snippet", {"contents": " = "}]
      ]
    }
  ```
  }
  ```

  ⇧⌃; Add semicolon at end of line, insert new line

  ```js
  {
    "keys": ["shift+ctrl+;"],
    "command": "chain",
    "args": {
      "commands": [
        ["move_to", { "to": "eol" }],
        ["insert_snippet", {"contents": ";"}],
        ["run_macro_file", {"file": "res:Packages/Default/Add Line.sublime-macro"}]
      ]
    }
  ```
  }
  ```


  ⌃, Add comma at end of line

  ```js
  {
    "keys": ["ctrl+,"],
    "command": "chain",
    "args": {
      "commands": [
        ["move_to", { "to": "eol" }],
        ["insert_snippet", {"contents": ","}]
      ]
    }
  ```
  }
  ```

  ⇧⌃, Add comma at end of line, insert new line

  ```js
  {
    "keys": ["shift+ctrl+,"],
    "command": "chain",
    "args": {
      "commands": [
        ["move_to", { "to": "eol" }],
        ["insert_snippet", {"contents": ","}],
        ["run_macro_file", {"file": "res:Packages/Default/Add Line.sublime-macro"}]
      ]
    }
  ```
  }
  ```

  ⌃space, Add space between the last character

  ```js
  {
    "keys": ["ctrl+space"],
    "command": "chain",
    "args": {

      "commands": [
        ["move_to", { "to": "eol" }],
        ["move", {"by": "characters", "forward": false }],
        ["insert_snippet", {"contents": " "}],
      ]
    }
  ```
  }
  ```


  ```js
  {
    "keys": ["ctrl+o"],
    "command": "markdown_preview_select",
    "args": { "target": "browser" }
  }
  ```

  ⌃⌘L Sublime linter

  ```js
  {
    "keys": ["ctrl+super+l"],
    "command": "sublimelinter_show_errors",
    "args": {"action": "lint", "show_popup": true}
  }
  ```

Ruby Test
---------

  ⇧⌘R Run Single Test

  ```js
  {
    "keys": ["super+r"], "command": "run_single_ruby_test",
    "context": [

  ```js
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
  ```
    ]
  }
  ```

  ⌘R All Tests

  ```js
  {
    "keys": ["shift+super+r"], "command": "run_all_ruby_test",
      "context": [

  ```js
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby, source.rspec, text.gherkin.feature"
        }
  ```
      ]
  }
  ```

  ⌘R All Tests (RubyMine Style)

  ```js
  {
    "keys": ["shift+ctrl+f10"], "command": "run_all_ruby_test",
      "context": [

  ```js
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby, source.rspec, text.gherkin.feature"
        }
  ```
      ]
  }
  ```

  ⇧⌘E Run Last Test

  ```js
  {
    "keys": ["shift+super+e"], "command": "run_last_ruby_test",
    "context": [

  ```js
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
  ```
    ]
  }
  ```

  ⇧⌘E Run Last Test (RubyMine style)

  ```js
  {
    "keys": ["shift+f10"], "command": "run_last_ruby_test",
    "context": [

  ```js
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
  ```
    ]
  }
  ```

  ⇧⌘X Toggle Test Console

  ```js
  {
    "keys": ["shift+super+x"], "command": "show_test_panel" },

  ⇧⌥V Verify File

  ```js
  {
    "keys": ["shift+alt+v"], "command": "verify_ruby_file",
    "context": [

  ```js
      {
        "key": "selector",
        "operator": "equal",
                    "operand": "source.ruby"
      }
  ```
    ]
  }
  ```

  ⌘. Switch between code and test view default to split view

  ```js
  {
    "keys": ["super+period"],
    "command": "switch_between_code_and_test",
    "args": {"split_view": true},
    "context": [

  ```js
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
  ```
    ]
  }
  ```
