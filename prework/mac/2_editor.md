# Install VSCode Text Editor

Now it's time to install VSCode Text Editor, a sophisticated text editor for code, markup, and prose.

To get started, download [VSCode](https://code.visualstudio.com/download), and after it is installed, launch the application.

[VSCode's documentation](https://code.visualstudio.com/docs) is excellent. Review it now to familiarize yourself with the basics.

## Install shell commands

You'll find it useful to open files and directories in VSCode from the terminal, but that functionality needs to be configured first.

Open the **Command Palette** (⇧⌘P) and type `shell command` to find the **Shell Command: Install 'code' command in PATH** command.

Restart the terminal for the new $PATH value to take effect. You'll be able to type `code .` in any folder to start editing files in that folder. If VSCode opens, you're good to go.

If VSCode does not open, try the above process again. If it still does not work, we will remedy it during lab on the first day of class.

## Associate VSCode with Git

It's important to establish a default editor with Git (version control software) so that when Git opens files, that happens in your chosen editor.

Type the following command in your terminal:
`git config --global core.editor "code --wait"`

This command will not return any message unless there is an error.


### [⇐ Previous](1_terminal.md) | [Next ⇒](3_git.md)
