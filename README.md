# Bootstrap v4 Snippets for VS Code

![release badge](https://img.shields.io/github/v/release/ForestCrazy/bootstrap-v4-snippets-tool)
![license badge](https://img.shields.io/github/license/ForestCrazy/bootstrap-v4-snippets-tool)

A pack of **115** code snippets for Bootstrap toolkit.  
Latest supported version: *v4.3.1*

[Get Bootstrap here](https://getbootstrap.com/) 
Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.

## 🔗 Download

* [Visual Studio | Marketplace](https://marketplace.visualstudio.com/items?itemName=ForestCrazy.bootstrap-v4-snippets-tool)

## 🏁 Getting started

To start using the snippets simply type **bs4-** *snippet_name*.

* To preview the selected snippet click `CTRL+SPACEBAR`.  
* To use the selected snippet simply click `TAB`.

[Browse all snippets](https://github.com/ForestCrazy/bootstrap-v4-snippets-tool/blob/master/bootstrap-v4-snippets/snippets/snippets.json)

## 🖼️ Preview

![preview1.gif](https://i.imgur.com/gbRrW2r.gif)

## ⚓ Links

* [Issues](https://github.com/ForestCrazy/bootstrap-v4-snippets-tool/issues)
* [Changelog](https://github.com/ForestCrazy/bootstrap-v4-snippets-tool/blob/master/bootstrap-v4-snippets/CHANGELOG.md)

## 👨🏻‍💻 Compiling and testing guide

* All snippets are stored inside the `source` directory.
* To build the snippets execute `build-from-source.bat` file *(you will need to install .NET Core 2.2 or newer)*.
* Compiled snippets can be found in `bootstrap-v4-snippets/snippets/snippets.json`.
* To test the changes copy the file content `bootstrap-v4-snippets/snippets/snippets.json` and paste it inside `VS Code > F1 > Preferences: Configure User Snippets > html.json` 🎉
* To compile to .vsix(vs code extension) file execute `create-package.bat` file
* can be found in `bootstrap-v4-snippets/extension_name-version.vsix`.