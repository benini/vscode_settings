## Visual Studio Code (VSCode) Configuration Files

VSCode stores the `settings.json` and `keybindings.json` files in platform-specific locations:

### Windows
- `settings.json`: `%APPDATA%\Code\User\settings.json`
- `keybindings.json`: `%APPDATA%\Code\User\keybindings.json`

### macOS
- `settings.json`: `~/Library/Application Support/Code/User/settings.json`
- `keybindings.json`: `~/Library/Application Support/Code/User/keybindings.json`

### Linux
- `settings.json`: `~/.config/Code/User/settings.json`
- `keybindings.json`: `~/.config/Code/User/keybindings.json`

Additional user preferences files include:

- `extensions.json`: Configuration of enabled and disabled extensions, located in the same folder as `settings.json` and `keybindings.json`.
- Workspace settings: Workspace-specific settings saved in a `.vscode` folder inside the workspace, in a file named `settings.json`. These settings apply only to the specific workspace and override the global settings.

