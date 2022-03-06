# DevHaven

A color theme to customize my vscode by borrowing color elements from [NightOwl Theme](https://github.com/sdras/night-owl-vscode-theme).

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

### References

- [Night Owl Theme](https://github.com/sdras/night-owl-vscode-theme)
- [Base16 Terminal Colors](https://glitchbone.github.io/vscode-base16-term/)
- [Creating a VS Code theme](https://juhanajauhiainen.com/posts/how-to-create-your-own-vscode-theme)

### Color Choices

```js

// "statusBar.background": "#101d00",
// "statusBar.foreground": "#91ff00d0",

"statusBar.background": "#00ff93b3",
"statusBar.foreground": "#000000",
"statusBarItem.hoverBackground": "#2cff00",
"statusBarItem.remoteBackground": "#00ff93b3",
"statusBarItem.remoteForeground": "#000000",

/* --- DevHaven
    "statusBar.background": "#00ff93b3",
    "statusBar.foreground": "#000000",
    "statusBar.border": "#262A39",
    "statusBar.debuggingBackground": "#202431",
    "statusBar.debuggingForeground": null,
    "statusBar.debuggingBorder": "#1F2330",
    "statusBar.noFolderForeground": null,
    "statusBar.noFolderBackground": "#011627",
    "statusBar.noFolderBorder": "#25293A",
    "statusBarItem.remoteBackground": "#00ff93b3",
    "statusBarItem.remoteForeground": "#000000",
    "statusBarItem.activeBackground": "#202431",
    "statusBarItem.hoverBackground": "#2cff00",
    "statusBarItem.prominentBackground": "#202431",
    "statusBarItem.prominentHoverBackground": "#202431",
*/

/* --- Devhaven Muted Staus Bar
    "statusBar.background": "#002c0b1f",
    "statusBar.foreground": "#00ff93b3",
    "statusBar.border": "#262A39",
    "statusBar.debuggingBackground": "#202431",
    "statusBar.debuggingForeground": null,
    "statusBar.debuggingBorder": "#1F2330",
    "statusBar.noFolderForeground": null,
    "statusBar.noFolderBackground": "#011627",
    "statusBar.noFolderBorder": "#25293A",
    "statusBarItem.remoteBackground": "#00ff93b3",
    "statusBarItem.remoteForeground": "#000000",
    "statusBarItem.activeBackground": "#1e3a35",
    "statusBarItem.hoverBackground": "#2bff004f",
    "statusBarItem.prominentBackground": "#202431",
    "statusBarItem.prominentHoverBackground": "#202431",

*/


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

"titleBar.activeBackground": "#002110",

"editorGroup.emptyBackground": "#011627",
"editorGroup.border": "#011627",
"editorGroup.dropBackground": "#7e57c273",
"editorGroupHeader.noTabsBackground": "#011627",
"editorGroupHeader.tabsBackground": "#052529",
"editorGroupHeader.tabsBorder": "#262A39",
"tab.activeBackground": "#073C42",
"tab.activeForeground": "#fdfdfd",
"tab.border": "#fafafa1a",
"tab.activeBorder": "#262A39",
"tab.unfocusedActiveBorder": "#263934",
"tab.inactiveBackground": "#91ff000a",
"tab.inactiveForeground": "#bee4bcbe",

"panel.background": "#00301c60",
"panel.border": "#5f977d",
"panelTitle.inactiveForeground": "#6dff96b0",


"terminal.background": "#031A16",
"terminal.foreground": "#81B5AC",
"terminalCursor.background": "#81B5AC",
"terminalCursor.foreground": "#81B5AC",
"terminal.ansiWhite": "#ffffff",
"terminal.ansiBlack": "#011627",
"terminal.ansiBlue": "#82AAFF",
"terminal.ansiCyan": "#21c7a8",
"terminal.ansiGreen": "#22da6e",
"terminal.ansiMagenta": "#C792EA",
"terminal.ansiRed": "#EF5350",
"terminal.ansiYellow": "#c5e478",
"terminal.ansiBrightWhite": "#ffffff",
"terminal.ansiBrightBlack": "#575656",
"terminal.ansiBrightBlue": "#82AAFF",
"terminal.ansiBrightCyan": "#7fdbca",
"terminal.ansiBrightGreen": "#22da6e",
"terminal.ansiBrightMagenta": "#C792EA",
"terminal.ansiBrightRed": "#EF5350",
"terminal.ansiBrightYellow": "#ffeb95",
"terminal.selectionBackground": "#1b90dd4d",
```
