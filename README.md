This is just my vscode template for setup new godoto projects

## install vscode extensions

```
ext install 1YiB.rust-bundle
ext install vadimcn.vscode-lldb
ext install actboy168.tasks
ext install augustocdias.tasks-shell-input
ext install IgorSbitnev.error-gutters
```

## godot and gdext sources

checkout gdext and godot sources and set the paths in the *.vscode/settings.json*

```json
{
  "gdext.path": "D:\\Godot4\\gdext",
  "godot.src": "D:\\Godot4\\godot",
```

## Modify vscode workspace file
```json
"settings": {
  "godotTools.editorPath.godot4": "d:/Godot4/IDE/Godot_v4.2.1-stable_win64/Godot_v4.2.1-stable_win64.exe",
  "godotTools.editorPath.godot4_console": "d:/Godot4/IDE/Godot_v4.2.1-stable_win64/Godot_v4.2.1-stable_win64_console.exe"
}
```

> [!NOTE]
> works with linux paths too

---

thats all have fun with it
