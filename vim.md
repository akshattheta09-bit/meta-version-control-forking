How to use vim as a text editor in terminal for git commit messages and other git-related tasks.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Setting vim as the default editor for git
To set vim as the default editor for git, you can use the following command:
git config --global core.editor "vim"
This command configures git to use vim whenever it needs to open an editor, such as when writing commit messages.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Basic vim commands for git users
Here are some basic vim commands that are useful when working with git:
- i : Enter insert mode to start typing your commit message.
- Esc : Exit insert mode and return to normal mode.
- :w : Save the current file (write changes).
- :q : Quit vim.
- :wq : Save changes and quit vim.
- :q! : Quit vim without saving changes.
- :x : Save changes and quit vim (similar to :wq).
- :set number : Show line numbers (useful for navigating large commit messages).
- /<text> : Search for <text> in the file.
- n : Move to the next occurrence of the searched text.
- N : Move to the previous occurrence of the searched text.


Exiting vim after writing a commit message
After writing your commit message in vim, follow these steps to exit and save the message:
1. Press Esc to ensure you are in normal mode.
2. Type :wq and press Enter to save the commit message and exit vim.
If you want to exit without saving the commit message, you can type :q! and press Enter.



How to use vim in general for writing codes and all that Stuff

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Vim is a powerful text editor that can be used for writing code, configuration files, and more. Here are some general tips for using vim effectively:
- Navigation:
  - h, j, k, l : Move left, down, up, right.
  - gg : Go to the beginning of the file.
  - G : Go to the end of the file.
  - w : Move to the beginning of the next word.
  - b : Move to the beginning of the previous word.
- Editing:
  - x : Delete the character under the cursor.
  - dd : Delete the current line.
  - yy : Copy (yank) the current line.
  - p : Paste the copied or deleted text after the cursor.
  - u : Undo the last change.
  - Ctrl + r : Redo the last undone change.
- Visual Mode:
  - v : Enter visual mode to select text.
  - V : Enter visual line mode to select entire lines.
  - Ctrl + v : Enter visual block mode to select a block of text.
- Saving and Exiting:
  - :w : Save the current file.
  - :q : Quit vim.
  - :wq : Save and quit vim.
  - :q! : Quit without saving changes.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
other useful vim commands
- :set number : Show line numbers.
- :set relativenumber : Show relative line numbers.
- :syntax on : Enable syntax highlighting.
- :set tabstop=4 : Set the number of spaces a tab counts for.
- :set shiftwidth=4 : Set the number of spaces to use for each step of (auto)indent.
- :set expandtab : Use spaces instead of tabs.
- :%s/old/new/g : Replace all occurrences of 'old' with 'new' in the entire file.
- :help <command> : Get help on a specific vim command.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~