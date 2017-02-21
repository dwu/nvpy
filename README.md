# nvPY

See <https://github.com/cpbotha/nvpy> for original documentation.

## Changes in this fork

* Keybindings
	* Delete current line or selection with `Control-d`; delete current note with `Control-Shift-d`
	* Delete previous word with `Control-BackSpace`
	* Change `Control-s` keybinding to trigger local file sync
* Interface
	* Configurable note text pane size (config file options `text_width` and `text_height`)
* Features
	* Experimental (!) quick and dirty note archiving implementation (`Control-Shift-a`). Note is moved to the `Archive` sub-folder of the note folder with a modifieddate prefix.
