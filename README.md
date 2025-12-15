# Highlighting for the Basin language

@TODO Update the icon to Basin instead of BTB

This plugin provies syntax highlighting for the Basin language and makes sure vscode recognizes text in .bsn files as a programming language allowing you to toggle comments among other things.

![](img/syntax-example.png)

## Features

- Syntax highlighting for .bsn files

The extension does not support hints, suggestions or syntax errors, just highlighting. There are plans to implement a language server but that may be in 1-2 years (maybe more).

**WARNING:** The syntax highlighting does not fully reflect if code will compile or not. It is just a bit of color to make it more pleasant to work with.

## Installing

### From the Marketplace
1. Open Visual Studio Code.
2. Go to the Extensions view (`Ctrl+Shift+X`).
3. Search for "basin lang" and click **Install**.

### From VSIX
1. Download the `.vsix` file from [Releases](https://github.com/Emarioo/Basin/releases).
2. Open Visual Studio Code.
3. Go to the Extensions view, click `...`, and select **Install from VSIX...**.

### Building
To create `.vsix` package
```bash
vsce package
```

**NOTE**: This extension can be found here `https://github.com/Emarioo/basin-vscode-extension`.