### Install Sublime Text

Now it's time to install [Sublime Text](http://www.sublimetext.com/), a sophisticated text editor for code, markup, and prose.

To get started, download [Sublime Text 2](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%202.0.2%20x64%20Setup.exe) and run the installer. Again, go with the default installation options if you're feeling overwhelmed.

Once installed, use the Start Menu to launch Sublime Text 2.

![](http://i.imgur.com/mnR5naJ.png)

Next, navigate to the `Preferences > Settings - User` menu item.

Ensure the file contains the following preferences.

```
{
  "font_size": 15.0,
  "ensure_newline_at_eof_on_save": true,
  "rulers": [80],
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true
}
```

**WARNING:** Punctuation errors with either curly-brackets, double-quotes, colons, square-brackets, or commas will be highlighted in red. If one of these symbols is missing, Sublime Text will highlight the next closest symbol. Analyze the above example preferences carefully. :eyes:

Remember to save the file and you'll see something like this.

![](https://imgur.com/Gzz7ojR.png)

When you're done, close the file.

### [⇐ Previous](1_terminal.md) | [Next ⇒](3_git.md)
