---
date created: 2024-02-01T03:49:34
date modified: 2025-01-21T11:23:52
---

# Terminal Cheat Sheet

## Navigation

- `ls`: List files and directories
	- `ls -a`: List all files and directories
	- `ls -l`: List files and directories in long format
	- `ls -la`: List all files and directories in long format
- `cd <dir>`: Change directory
	- `cd..`: Go up one directory
	- `cd ~`: Go to home directory
	- `cd -`: Go to previous directory

## File Management

- `mkdir <dir>`: Create a new directory
- `touch <file>`: Create a new file and modify last modified time
- `cp <from> <to>`: Copy a file or directory
- `mv <from> <to>`: Move a file or directory
- `rm <file|dir>`: Remove a file or directory
	- `rm -r <dir>`: Remove a directory and its contents
	- `rm -f <file|dir>`: Force remove a file or directory
	- `rm -rf <dir>`: Force remove a directory and its contents

## File Viewing

- `cat`: Print the contents of a file
- `less`: View the contents of a file

## File Editing

- `vim`: Use vim as a file editor
	- At the bottom left you see in which mode of vim you are currently in.
	- If it doest say anything, you are in "normal" mode. Here you may enter commands like:
		- `:w` to save a file
		- `:q` to exit the editor
		- `:wq` to save and exit the file
		- `:q!` to exit and discard changes
		- Or press specific keys, like:
			- `i` to start editing at your cursors position
			- `a` to start editing at the end of the word your cursor is on
		- If you are not in normal mode, but in editing mode for example, you can hit
			- `Esc` to get back to normal mode and save/exit the file.
- `nano`: Use nano as a file editor
	- Nano shows the available commands at the bottom.
	- The `^<Letter>` usually means a keyboard shortcut of `CTRL+<Letter>`, e.g.:
		- `^X Exit` -> `CTRL+X` to exit the file. You will be asked to save, discard or cancel, if you made changes without saving them before.
			- Hit `Y` to save and exit
			- Hit `N` to discard changes and exit
			- Hit `CTRL+C` to cancel exiting the file
