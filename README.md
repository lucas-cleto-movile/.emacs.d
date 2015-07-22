# This is my personal emacs settings

This conf is based on: 
[CLOJURE for the BRAVE and TRUE](http://www.braveclojure.com/basic-emacs/)!

## Keybindings

Conventions:
- <kbd>C-[something]</kbd> : Control + <kbd>[something]</kbd>
- <kbd>M-[something]</kbd> : Option + <kbd>[something]</kbd>
- <kbd>CMD-[something]</kbd> : Command + <kbd>[something]</kbd>

#### Buffers and Files

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-g</kbd> | Quit Emacs commands
<kbd>C-x b [buffer-name]</kbd> | Create/Open a buffer
<kbd>C-x k [buffer-name]</kbd> | Kill a buffer
<kbd>C-x C-f [file-path]</kbd> | Create/Open a file
<kbd>C-x C-s</kbd> or <kbd>CMD-s</kbd> | Save a file
<kbd>C-x 1</kbd> | Delete other windows

#### Meta and Packages

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>M-x [function-name]</kbd> | Run a function
<kbd>C-h [function-name]</kbd> |	Describe function
<kbd>C-h k [keybinding]</kbd> | Describes the function bound to the <kbd>keybinding</kbd>
<kbd>M-x package-list-packages</kbd> <br/> <kbd>i</kbd>-nstall, <kbd>u</kbd>-nmark, <kbd>d</kbd>-elete, <kbd>x</kbd>-ecute, <kbd>r</kbd>-efresh, <kbd>h</kbd>-elp, <kbd>q</kbd>-uit | List available packages
<kbd>M-x package-install</kbd> ... <kbd>[package-name]</kbd> | Install a package from the local package list
<kbd>M-x package-refresh-contents</kbd> | Refresh the local package list

#### Core Editing and Movement

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-k</kbd> | Kill all text after point on the current line
<kbd>C-/</kbd> or <kbd>CMD-z</kbd> | Undo
<kbd>C-a</kbd> | Move to beginning of line
<kbd>M-m</kbd> | Move to the first non-whitespace character on the line
<kbd>C-e</kbd> | Move to end of line
<kbd>M-f</kbd> or <kbd>M-<kbd>right</kbd></kbd>| Move forward one word
<kbd>M-b</kbd> or <kbd>M-<kbd>left</kbd></kbd>| Move backward one word
<kbd>C-s</kbd> | Regex search for text in the current buffer and move to it. Hit <kbd>C-s</kbd> again to move to the next match
<kbd>C-r</kbd> | Same as above, but search in reverse
<kbd>M-<</kbd> | Move to beginning of buffer
<kbd>M-></kbd> | Move to end of buffer
<kbd>M-g g</kbd> ... <kbd>[number]</kbd> | Go to line <kbd>[number]</kbd>
<kbd>C-<kbd>space</kbd></kbd> | Create a region setting the mark
<kbd>M-x replace-string</kbd> ... <kbd>[string 1]</kbd> ... <kbd>[string 2]</kbd> | Replace <kbd>[string 1]</kbd> with <kbd>[string 2]</kbd> in the current region
<kbd>M-/</kbd> | Cycle through possible expansions of the text before point
<kbd>M-\</kbd> | Delete all spaces and tabs around point
<kbd><kbd>tab</kbd></kbd> | Indent line
<kbd>C-j</kbd> | New indented line

#### Kill Ring

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-w</kbd> |	Kill region
<kbd>M-w</kbd> |	Copy region to kill ring
<kbd>C-y</kbd> |	Yank ("paste")
<kbd>M-y</kbd> |	Cycle through kill ring after yanking
<kbd>M-d</kbd> |	Kill word
<kbd>C-k</kbd> |	Kill line


