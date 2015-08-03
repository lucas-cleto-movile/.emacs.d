# This is my personal emacs settings

This conf is based on: 
[CLOJURE for the BRAVE and TRUE](http://www.braveclojure.com/basic-emacs/)!

## Keybindings

Conventions:
- <kbd>C-[something]</kbd> : Control + <kbd>[something]</kbd>
- <kbd>M-[something]</kbd> : Option + <kbd>[something]</kbd>
- <kbd>CMD-[something]</kbd> : Command + <kbd>[something]</kbd>

#### Emacs Basics and Meta

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-x C-c</kbd> | Exit Emacs
<kbd>M-x [function-name]</kbd> | Run a function
<kbd>C-h [function-name]</kbd> |	Describe function
<kbd>C-h k [keybinding]</kbd> | Describes the function bound to the <kbd>keybinding</kbd>

#### Buffers and Files

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-g</kbd> | Quit Emacs commands
<kbd>C-x b [buffer-name]</kbd> | Create/Open a buffer
<kbd>C-x k [buffer-name]</kbd> | Kill a buffer
<kbd>C-x C-f [file-path]</kbd> | Create/Open a file
<kbd>C-x C-s</kbd> or <kbd>CMD-s</kbd> | Save a file
<kbd>C-x 1</kbd> | Delete other windows

#### Packages

Keybinding         | Description
-------------------|------------------------------------------------------------
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

#### Windows and Frames

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-x o</kbd> | Switch cursor to another window. Go ahead and try this now to switch between your Clojure file and the REPL
<kbd>C-x 1</kbd> | Delete all other windows. This doesn't close your buffers and it won't cause you to lose any work. It just un-splits your frame.
<kbd>C-x 2</kbd> | Split window, above and below
<kbd>C-x 3</kbd> | Split window, side by side
<kbd>C-x 0</kbd> | Delete current window

#### Kill Ring

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-w</kbd> |	Kill region
<kbd>M-w</kbd> |	Copy region to kill ring
<kbd>C-y</kbd> |	Yank ("paste")
<kbd>M-y</kbd> |	Cycle through kill ring after yanking
<kbd>M-d</kbd> |	Kill word
<kbd>C-k</kbd> |	Kill line

#### REPL

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>C-x C-e</kbd> | Send the expression immediately preceding point to nrepl
<kbd>C-c M-n</kbd> | Set the namespace to the namespace listed at the top of your current file
<kbd>C-c C-k</kbd> | Compile and run the current file within the CIDER session
<kbd>C-<kbd>up</kbd> and C-<kbd>down</kbd></kbd> | Cycle through CIDER history 
<kbd>q</kbd> | Culose the stack trace and go back to CIDER 

#### Paredit

Keybinding         | Description
-------------------|------------------------------------------------------------
<kbd>M-x paredit-mode</kbd> |  Toggles paredit mode on and off
<kbd>M-(</kbd> | Paredit wrap round
<kbd>C-<kbd>Shift</kbd>-<kbd>right</kbd></kbd> | Slurp a element
<kbd>C-<kbd>Shift</kbd>-<kbd>left</kbd></kbd> | Barf a element
<kbd>C-M-f, C-M-b</kbd> | Move to the opening/closing parenthesis
