# git/homelab/vscode

## VS Code Extensions

The `vscode-extensions.txt` file lists all installed VS Code extensions.

### To generate this file

```powershell
code --list-extensions > c:\git\homelab\vscode\vscode-extensions.txt
```

## VS Code Settings

The `settings.json` file contains user-specific VS Code settings. This file is typically located at:

* Windows: `%APPDATA%\Code\User\settings.json`
* macOS: `$HOME/Library/Application Support/Code/User/settings.json`
* Linux: `$HOME/.config/Code/User/settings.json`

It's recommended to copy the relevant settings from your user `settings.json` to
`c:\git\homelab\vscode\settings.json` to keep a synchronized copy of important settings under
version control.
