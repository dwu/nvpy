# nvPY

Fork of cpbotha's great note-taking application *nvpy* with a couple of tweaks to adapt it for my needs.

See <https://github.com/cpbotha/nvpy> for the original documentation.

## Changes in this fork

* Keybindings
	* Change `Control-s` keybinding to trigger local file sync instantly
* Interface
	* Configurable note text pane size (config file options `text_width` and `text_height`)
* Features
	* Delete current line or selection with `Control-d`; delete current note with `Control-Shift-d`
	* Delete previous word with `Control-BackSpace`
	* Experimental (!) quick and dirty note archiving implementation (`Control-Shift-a`). Note is moved to the `Archive` sub-folder of the note folder with a modifieddate prefix.
	* Toggle checkbox (`[ ]`/`[x]`) in current line with `Alt-c`
