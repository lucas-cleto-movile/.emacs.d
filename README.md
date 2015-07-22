# This is my personal emacs settings

This conf is based on: 
[CLOJURE for the BRAVE and TRUE](http://www.braveclojure.com/basic-emacs/)!

## Keybindings

#### Buffers and Files

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-g</kbd> | Quit Emacs commands
<kbd>C-x b [buffer-name]</kbd> | Create/Open a buffer
<kbd>C-x k [buffer-name]</kbd> | Kill a buffer
<kbd>C-x C-f [file-path]</kbd> | Create/Open a file
<kbd>C-x C-s</kbd> or <kbd>CMD-s</kbd> | Save a file

#### Meta and Packages

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>M-x [function-name]</kbd> | Run a function
<kbd>M-x package-list-packages</kbd> <br/> <kbd>i</kbd>-nstall, <kbd>u</kbd>-nmark, <kbd>d</kbd>-elete, <kbd>x</kbd>-ecute, <kbd>r</kbd>-efresh, <kbd>h</kbd>-elp, <kbd>q</kbd>-uit | List available packages
<kbd>M-x package-install</kbd> ... <kbd>[package-name]</kbd> | Install a package from the local package list
<kbd>M-x package-refresh-contents</kbd> | Refresh the local package list

#### Core Editing

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-y</kbd> | Paste
<kbd>C-k</kbd> | Kill all text after point on the current line
<kbd>C-/</kbd> or <kbd>CMD-z</kbd> | Undo
<kbd>C-a</kbd> | Move to beginning of line
<kbd>M-m</kbd> | Move to the first non-whitespace character on the line
<kbd>C-e</kbd> | Move to end of line
<kbd>M-f</kbd> | Move forward one word
<kbd>M-b</kbd> | Move backward one word
<kbd>C-s</kbd> | Regex search for text in the current buffer and move to it. Hit <kbd>C-s</kbd> again to move to the next match
<kbd>C-r</kbd> | Same as above, but search in reverse
<kbd>M-<</kbd> | Move to beginning of buffer
<kbd>M-></kbd> | Move to end of buffer
<kbd>M-gg</kbd> ... <kbd>[number]</kbd> | Go to line <kbd>[number]</kbd>
<kbd>C-space</kbd> | Create a region setting the mark

