### [Godot Engine v4](https://godotengine.org)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/godot.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/godot/archive/main.zip) option and unzip them.

#### Activating theme

1. Navigate to `Editor -> Editor Settings -> Interface -> Theme`;
2. Set the `Base Color` to `#282a36`;
3. Set the `Accent Color` to `#6272a4`;
4. Set the `contrast` to `0.21`;
5. Leave the `Icon Saturation` at `1.0`;
6. Set the Text Editor theme:
   - Windows: move the `dracula.tet` to ` %APPDATA%\Godot\text_editor_themes\`;
   - Linux: move the `dracula.tet` to `$HOME/.config/godot/text_editor_themes`;
   - MacOS: move the `dracula.tet` to `~/Library/Application Support/Godot/text_editor_themes/`;
   - Steam: move the `dracula.tet` to `steamapps/common/Godot Engine/editor_data/text_editor_themes/`.
7. Go to `Editor -> Editor Settings -> General -> Text Editor -> Theme`;
8. Select `Dracula` from the `Color Theme` dropdown;
9. Boom, it's working! ✨

---

### [Godot Engine v3](https://godotengine.org)

> The Dracula Theme for the Godot Engine v3 is no longer maintained; we recommend the latest version, available above.

<details>
  <summary>Version 3</summary>

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/godot.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/godot/archive/main.zip) option and unzip them.

#### Activating theme

##### Linux

1. Start Godot for the first time and close it;
2. Go to the `theme folder` and copy the `PATH`;
3. 👉🏻 `cat 'OBTAINED_PATH/v3-theme.tres' >> 'GODOT_PATH/editor_settings-3.tres'`
   GODOT_PATH being `$HOME/.config/godot` if installed from [Godot](https://godotengine.org)
   Or `$HOME/.steam/steam/steamapps/common/Godot Engine/editor_data` if installed with [Steam](https://store.steampowered.com).

##### Windows

1. Start Godot for the first time and close it;
2. Go to the `theme folder` and copy the `PATH`;
3. 👉🏻 `Get-Content 'OBTAINED_PATH\v3-theme.tres' | Add-Content 'GODOT_PATH\editor_settings-3.tres'`
   GODOT_PATH being `$env:APPDATA\Godot` if installed from [Godot](https://godotengine.org)
   Or `C:\Program Files (x86)\Steam\steamapps\common\Godot Engine\editor_data` if installed with [Steam](https://store.steampowered.com)

</details>
