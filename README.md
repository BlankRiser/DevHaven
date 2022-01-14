# DevHaven

A color theme to customize my vscode.

### Color Choices

```js

"statusBar.background": "#101d00",
"statusBar.foreground": "#91ff00d0",

"sideBar.background": "#000000",
"sideBar.foreground": "#89bbaa",
"sideBar.border": "#91ff0044",
"sideBarTitle.foreground": "#91ff00",

"activityBar.background": "#052529",
"activityBar.foreground": "#91ff00",
"activityBar.border": "#91ff0011",

"tab.activeBackground": "#91ff0018",
"tab.activeForeground": "#91ff00",

"editorCursor.foreground": "#91ff00",

"editor.selectionHighlightBackground": "#0A464E",
"editor.selectionHighlightBackground": "#6ff5913f",
"editor.lineHighlightBackground": "#073C42",

"editorGutter.background": "#052529",
"editorGutter.modifiedBackground": "#e5ff00f6",
"editorGutter.addedBackground": "#91ff00cc",
"editorGutter.deletedBackground": "#ff0000cc",
"editorGutter.foldingControlForeground": "#91ff00cc",

```

### Build Theme from Source

- Install [VS Code Extension Manager](https://github.com/microsoft/vscode-vsce)

```node
npm i -g vsce
```

- Use `vsce` to package the theme

```node
vsce package
```

- [Install vsix package through VS Code](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix) that is generated in source folder

```
code --install-extension <package_name>.vsix
```
