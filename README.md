# fedmenu
File Explorer for dmenu

fedmenu is a small script that lets you quickly navigate to a file or directory by utilizing dmenu. You are then given the option to open that file or directory in whatever program you chose (with dmenu) or by using one of several "Open with" shortcuts that will appear in your directory list.

To install, put the script in a $PATH directory and assign a keyboard shortcut to launch fedmenu. Make sure the file is executable. Open the script file and configure program shortcuts to your liking. For example, you would most definitely want to change the default terminal.

Dependencies:
- dmenu
(Common GNU tools)
- realpath
- dirname
- compgen

