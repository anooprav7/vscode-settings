# vscode-settings
My VSCode settings

## User Settings
* Font - [Fira Code](https://vscodecandothat.com/#font-ligatures)
* Tab Size - 4

## Keyboard Shortcuts (OSX)
```
* shift + option + f  => Format code 
* command + b         => Toggle open/close of sidebar
* command + j         => Toggle open/close bottom bar 
* command + shift + t => Open last closed tab
* command + p         => Go to File (File search)
* control + g         => Go to Line number (in file)
* command + shift + f => Open Search for string pattern in project
* control + `         => Open Editor Terminal
* command + /         => Comment the line(s) of code using //
* fn + up/down arrow  => Page Up / Page Down
* option + w          => Select a text and press these keys to add tag before and after the text (htmltagwrap plugin)
```

### Cursor Control (Editing)
```
* shift + option + command + up/down/right/left => Grows the cursor in that direction
  - shift + option (while dragging with mouse)  => For selective vertical selection
* option + mouse-click                          => Put multiple cursors at different positions
* shift + command + L                           => Create cursors on all occurrences of a string
  - select one instance of a string e.g. background-color and press ⇧⌘L. Start typing.
  
* shift + option + up/down                      => Copy a line and insert it above or below the current position
* option + up/down                              => Move an entire line or selection of lines up or down
* shift + command + k                           => Delete the entire line
```

### Navigating through code 
```
* command + p -> type @  => Organises your code into methods and properties in the order they were written
              -> type @: => Groups the methods and properties (Eg. Variables and functions)
              -> type :  => Allows to jump to a line number (Also tells total line numbers)
              -> type ?  => Lists and shows all the symbols (like above) you can use
* command + option + [or]   => Folding and Unfolding code sections (Eg. functions, classes etc)
  - command + K command + 0 => Fold all sections
  - command + K command + J => Unfold all sections
```

## Custom Keybindings (keybindings.json)
```
* commmand + shift + / => Toggle Block comment /* */
```

## Extensions list 
[Add code to shell command](https://code.visualstudio.com/docs/setup/mac)

This command gives the plugin list and orders them in a direct install format
```
code --list-extensions | xargs -L 1 echo code --install-extension
```

Run the following in the terminal to install plugins
```
code --install-extension bradgashler.htmltagwrap
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
code --install-extension CoenraadS.bracket-pair-colorizer
code --install-extension eg2.vscode-npm-script
code --install-extension esbenp.prettier-vscode
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension kamikillerto.vscode-colorize
code --install-extension kisstkondoros.vscode-gutter-preview
code --install-extension naumovs.color-highlight
code --install-extension pflannery.vscode-versionlens
code --install-extension pranaygp.vscode-css-peek
code --install-extension robertohuertasm.vscode-icons
code --install-extension spywhere.guides
code --install-extension wix.vscode-import-cost
code --install-extension flowtype.flow-for-vscode
```

## Emmet Shortcuts
```
! + tab => (in an html file) generates the basic template for index.html
```

## TODO
* Add JS Snippets
https://code.visualstudio.com/docs/editor/userdefinedsnippets
https://adtmag.com/blogs/dev-watch/2017/05/vs-code-snippets.aspx
* Add CSS Snippets
* Add React Snippets
