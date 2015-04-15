File Management
---------------

  Open Keybindings file `⌥⌘,`

  ```js
  {
    "keys": ["alt+super+,"],
    "command": "open_file",
    "args": { "file": "${packages}/User/Default (OSX).sublime-keymap" }
  }
  ```

  Rename file `⇧⌃⌥⌘R`

  ```js
  {
    "keys": ["super+alt+ctrl+shift+r"],
    "command": "side_bar_rename"
  }
  ```

   Move file `⇧⌃⌥⌘M`

  ```js
  {
    "keys": ["super+alt+ctrl+shift+m"],
    "command": "side_bar_move"
  }
  ```

  New file `⌘N`

  ```js
  {
    "keys": ["super+n"],
    "command": "advanced_new_file_new"
  }
  ```

  Open Latest Migration `⇧⌘M`

  ```js
  {
    "keys": ["shift+super+m"],
    "command": "rails_latest_migration"
  }
  ```

  Show file in sidebar `⌃⌘R`

  ```js
  {
    "keys": ["ctrl+super+r"],
    "command": "reveal_in_side_bar"
  }
  ```

Limit cycling to group
----------------------

  Cycle previous view within group `⇧⌘[`

  ```js
  {
    "keys": ["super+shift+["],
    "command": "prev_view_in_group"
  }
  ```

  Cycle next view within group `⇧⌘]`

  ```js
  {
    "keys": ["super+shift+]"],
    "command": "next_view_in_group"
  }
  ```

Find
----

  Find and Replace in file by default `⌘F`

  ```js
  {
    "keys": ["super+f"],
    "command": "show_panel",
    "args": {"panel": "replace"}
  }
  ```

  Find and Replace in project by default `⇧⌘F`

  ```js
  {
    "keys": ["super+shift+f"],
    "command": "show_panel",
    "args": {"panel": "find_in_files"}
  }
  ```

  Replace next match `⌘⌥F`

  ```js
  {
    "keys": ["super+alt+f"],
    "command": "replace_next"
  }
  ```

  Find next match `⌘G`

  ```js
  {
    "keys": ["super+g"],
    "command": "find_next"
  }
  ```

  Find previous match `⇧⌘G`

  ```js
  {
    "keys": ["super+shift+g"],
    "command": "find_prev"
  }
  ```

  Replace selection `⌥⌘F`

  ```js
  {
    "keys": ["alt+super+f"],
    "command": "replace_next"
  }
  ```

  Next match `⌘G`

  ```js
  {
    "keys": ["super+g"],
    "command": "find_next"
  }
  ```

  Previous match `⇧⌘G`

  ```js
  {
    "keys": ["shift+super+g"],
    "command": "find_prev"
  }
  ```


Multiple Cursors
----------------

  Skip selection `⌥⌘D`

  ```js
  {
    "keys": ["alt+super+d"],
    "command": "find_under_expand_skip"
  }
  ```

Text commands
-------------

  Paste and indent by default `⌘V`

  ```js
  {
    "keys": ["super+v"],
    "command": "paste_and_indent"
  }
  ```

  Sort lines `F5`

  ```js
  {
    "keys": ["f5"],
    "command": "sort_lines",
    "args": {"case_sensitive": false}
  }
  ```

Window Management
-----------------

  Close All windows `⇧⌃⌥⌘W`

  ```js
  {
    "keys": ["shift+ctrl+alt+super+w"],
    "command": "close_all"
  }
  ```

  Toggle Drawer `⌃⌥⌘D`

  ```js
  {
    "keys": ["ctrl+alt+super+d"],
    "command": "toggle_side_bar"
  }
  ```

  Toggle Mini Map `⌃⌥⌘M`

  ```js
  {
    "keys": ["ctrl+alt+super+m"],
    "command": "toggle_minimap"
  }
  ```

  Reopen tab `⇧⌘T`

  ```js
  {
    "keys": ["shift+super+t"],
    "command": "reopen_last_file"
  }
  ```

Text case
---------

  Uppercase `⌥⌘U`

  ```js
  {
    "keys": ["ctrl+alt+super+u"],
    "command": "upper_case"
  }
  ```

  Lowercase `⌥⌘L`

  ```js
  {
    "keys": ["alt+super+l"],
    "command": "lower_case"
  }
  ```

  Titlecase `⌃⌥⌘U`

  ```js
  {
    "keys": ["alt+super+u"],
    "command": "title_case"
  }
  ```

Text Insertion
-----------------

  Pipe Quotes `⇧⌃|`

  ```js
  {
    "keys": ["shift+ctrl+\\"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby/pipe-quotes.sublime-snippet"}
  }
  ```

  Hash Rocket `⌥⌘=`

  ```js
  {
    "keys": ["alt+super+="],
    "command": "insert_snippet",
    "args": {"contents": "=>"}
  }
  ```

  Spermy lock operator `⌥⌘\``

  ```js
  {
    "keys": ["alt+super+`"],
    "command": "insert_snippet",
    "args": {"contents": "~>"}
  }
  ```

  Insert right parens `⌃0`

  ```js
  {
    "keys": ["ctrl+0"],
    "command": "insert_snippet",
    "args": {"contents": ")"}
  }
  ```

  Insert left parens `⌃9`

  ```js
  {
    "keys": ["ctrl+9"],
    "command": "insert_snippet",
    "args": {"contents": "("}
  }
  ```

  Insert double quotes `⌃'`

  ```js
  {
    "keys": ["ctrl+'"],
    "command": "insert_snippet",
    "args": {"contents": "\""}
  }
  ```

  Stabby Arrow `⌥⌘-`

  ```js
  {
    "keys": ["alt+super+-"],
    "command": "insert_snippet",
    "args": {"contents": "->"}
  }
  ```

  To Underscore `⇧⌥⌘_`

  ```js
  {
    "keys": ["shift+ctrl+-"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/sh-string-to-underline.sublime-snippet"}
  }
  ```

  Convert Hash Rockets `⌃⌥⌘=`

  ```js
  {
    "keys": ["ctrl+alt+super+="],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-hash-convert.sublime-snippet"}
  }
  ```

  String to Symbol `⇧⌃:`

  ```js
  {
    "keys": ["shift+ctrl+;"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-symbolize.sublime-snippet"}
  }
  ```

  Symbol to String `⇧⌘"`

  ```js
  {
    "keys": ["shift+super+'"],
    "command": "insert_snippet",
    "args": {"name": "Packages/User/snippets/ruby-unsymbolize.sublime-snippet"}
  }
  ```

  Color picker `⌥⌘C`

  ```js
  {
    "keys": ["alt+super+c"], "command": "color_pick"
  }
  ```

  Add semicolon at end of line `⌃;`

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
  }
  ```

  Add == at end of line `⌃=`

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
  }
  ```

  Add semicolon at end of line, insert new line `⇧⌃;`

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
  }
  ```


  Add comma at end of line `⌃,`

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
  }
  ```

  Add comma at end of line, insert new line `⇧⌃,`

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
  }
  ```

  Add space between the last character `⌃⎵`

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
  }
  ```


  ```js
  {
    "keys": ["ctrl+o"],
    "command": "markdown_preview_select",
    "args": { "target": "browser" }
  }
  ```

  Sublime linter `⌃⌘L`

  ```js
  {
    "keys": ["ctrl+super+l"],
    "command": "sublimelinter_show_errors",
    "args": {"action": "lint", "show_popup": true}
  }
  ```

Ruby Test
---------

  Run Single Test `⇧⌘R`

  ```js
  {
    "keys": ["super+r"], "command": "run_single_ruby_test",
    "context": [
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
    ]
  }
  ```

  All Tests `⌘R`

  ```js
  {
    "keys": ["shift+super+r"], "command": "run_all_ruby_test",
      "context": [
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby, source.rspec, text.gherkin.feature"
        }
      ]
  }
  ```

  All Tests (RubyMine Style) `⌘R`

  ```js
  {
    "keys": ["shift+ctrl+f10"], "command": "run_all_ruby_test",
      "context": [
        {
          "key": "selector",
          "operator": "equal",
          "operand": "source.ruby, source.rspec, text.gherkin.feature"
        }
      ]
  }
  ```

  Run Last Test `⇧⌘E`

  ```js
  {
    "keys": ["shift+super+e"], "command": "run_last_ruby_test",
    "context": [
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
    ]
  }
  ```

  Run Last Test (RubyMine style) `⇧⌘E`

  ```js
  {
    "keys": ["shift+f10"], "command": "run_last_ruby_test",
    "context": [
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
    ]
  }
  ```

  Toggle Test Console `⇧⌘X`

  ```js
  {
    "keys": ["shift+super+x"], "command": "show_test_panel"
  }
  ```

  Verify File `⇧⌥V`

  ```js
  {
    "keys": ["shift+alt+v"], "command": "verify_ruby_file",
    "context": [
      {
        "key": "selector",
        "operator": "equal",
                    "operand": "source.ruby"
      }
    ]
  }
  ```

  Switch between code and test view default to split view `⌘.`

  ```js
  {
    "keys": ["super+period"],
    "command": "switch_between_code_and_test",
    "args": {"split_view": true},
    "context": [
      {
        "key": "selector",
        "operator": "equal",
        "operand": "source.ruby, source.rspec, text.gherkin.feature"
      }
    ]
  }
  ```
