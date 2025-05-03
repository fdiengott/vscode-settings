# VSCode Keybindings

The following should live in the `keybindings.json` file in your VSCode settings directory.

```json
[
  {
    "key": "h",
    "command": "editor.action.scrollLeftHover",
    "when": "editorHoverFocused"
  },
  {
    "key": "j",
    "command": "editor.action.scrollDownHover",
    "when": "editorHoverFocused"
  },
  {
    "key": "k",
    "command": "editor.action.scrollUpHover",
    "when": "editorHoverFocused"
  },
  {
    "key": "l",
    "command": "editor.action.scrollRightHover",
    "when": "editorHoverFocused"
  },
  {
    "key": "-",
    "command": "workbench.action.toggleSidebarVisibility",
    "when": "filesExplorerFocus && !inputFocus"
  },
  {
    "key": "a",
    "command": "explorer.newFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "f",
    "command": "explorer.newFolder",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "r",
    "command": "renameFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "x",
    "command": "filesExplorer.cut",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "y",
    "command": "filesExplorer.copy",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "p",
    "command": "filesExplorer.paste",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !explorerResourceReadonly && !inputFocus"
  }
]
```
