# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file that defines the location of the snippet file and specifies the language of the snippets.
* `snippets/snippets.code-snippets` - the file containing all snippets.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that your snippets are proposed on IntelliSense.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.

## Resources

* [YOUTUBE | Traversy Media - Creating A Simple VSCode Extension](https://youtu.be/srwsnNhiqv8)
* [Visual Studio Code | Your First Extension](https://code.visualstudio.com/api/get-started/your-first-extension)
* [Visual Studio Code | Publishing Extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

## Packaging

The extension is packaged using `vsce`, short for "Visual Studio Code Extensions". To package run:
```shell
vsce package
```
Note that you may need to update the path for `vsce` to be recognized. Adjust path values as needed.
```shell
IF EXIST C:\Users\nathanspencer\AppData\Roaming\npm SET PATH=%PATH%;C:\Users\nathanspencer\AppData\Roaming\npm
```
Packaging will create a .vsix file that can then be published.

## Publishing

Published extension can be managed at https://marketplace.visualstudio.com/manage/publishers/nathanspencer1.
You can also publish from terminal with:
```shell
vsce publish
```

