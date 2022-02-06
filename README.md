VSCode-AnB
===========================
<p align="center">
<img src="https://raw.githubusercontent.com/hiksuman/vscode-anb/master/images/icon.png" alt="drawing" height="100"/>
</p>
Syntax highlighting for the formal modelling language AnB in VS Code using TextMate.

# AnB Language
The formal modelling language AnB is used by the [ofmc](http://imm.dtu.dk/~samo/) tool and is based on the Alice-and-Bob notation. The file extension is `.AnB`.

# Install

From the Releases download the `.vsix` file and add it to VS Code as a local extension or soon possible to install it from VS Code Marketplace.

# Developement
To create the VS Code Extension file, `vsce package` is needed:
```
 npm -g install vsce
```
After modifying `anb.tmLanguage.json` recreate the package:
```
 vsce package
```

# Contribution

Feel free to contribute by opening an Issue or Pull Request.

# Other editors
[Syntax highlighter](https://github.com/anderslime/Syntax-highlighting-for-AnB) for Sublime Text by [anderslime](https://github.com/anderslime)


# License
[MIT](http://opensource.org/licenses/MIT)

