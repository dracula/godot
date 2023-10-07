### [Godot](https://godotengine.org)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/godot.git
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/godot/archive/master.zip) option and unzip them.

#### Activating theme

##### Linux

1. Start Godot for the first time and close it
2. Go to the theme folder and copy the PATH
3. ```cat 'OBTAINED_PATH/theme.tres' >> 'GODOT_PATH/editor_settings-4.tres'```

GODOT_PATH being ```$HOME/.config/godot``` if installed from [Godot](https://godotengine.org)

Or ```$HOME/.steam/steam/steamapps/common/Godot Engine/editor_data``` if installed with [Steam](https://store.steampowered.com)

##### Windows

1. Start Godot for the first time and close it
2. Go to the theme folder and copy the PATH
3. ```Get-Content 'OBTAINED_PATH\theme.tres' | Add-Content 'GODOT_PATH\editor_settings-4.tres'```

GODOT_PATH being ```$env:APPDATA\Godot``` if installed from [Godot](https://godotengine.org)

Or ```C:\Program Files (x86)\Steam\steamapps\common\Godot Engine\editor_data``` if installed with [Steam](https://store.steampowered.com)

##### macOS

1. Start Godot for the first time and close it.
2. Navigate to the theme folder and copy the PATH.
3. Using the terminal, run the following command:

    ```bash
    cat 'OBTAINED_PATH/theme.tres' >> "$HOME/Library/Application Support/Godot/editor_settings-4.tres"
    ```

GODOT_PATH being `$HOME/Library/Application Support/Godot` if installed from [Godot](https://godotengine.org) via `brew`.
