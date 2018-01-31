# Install VSCode Text Editor

Now it's time to install VSCode Text Editor, a sophisticated text editor for code, markup, and prose.

To get started, download [VSCode](https://code.visualstudio.com/download), and after it is installed, launch the application.

[VSCode's documentation](https://code.visualstudio.com/docs) is excellent. Review it now to familiarize yourself with the basics.

## Install shell commands

In Windows, installation of VSCode should automatically install a terminal shortcut to open the application by entering the command `code`, or to open all files in a directory, `code .`. Try this, and if it does not work on your laptop, we will remedy it during lab on the first day of class. 

## Associate VSCode with Git

It's important to establish a default editor with Git (version control software) so that when Git opens files, that happens in your chosen editor.

Type the following command in your terminal:
`git config --global core.editor "code --wait"`

This command will not return any message unless there is an error.


### [⇐ Previous](1_terminal.md) | [Next ⇒](3_git.md)
