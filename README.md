# Phoenix Lighting

Modern lighting for Final Fantasy XI on PhoenixXI, by Shuu: sun and moon shadows, lamps, character lighting, ambient occlusion, spell and weapon glows, weather, fog and water effects.

[Download the latest release](https://github.com/Shuu-37/phoenix-lighting-releases/releases/latest) · [All releases](https://github.com/Shuu-37/phoenix-lighting-releases/releases)

Each release provides `phoenixlighting.dll`, a complete ZIP package, and SHA-256 checksums. Shaders are embedded in the DLL.

## Requirements and installation

- Use Windows, Ashita v4 and dgVoodoo 2.87.5. In the Phoenix launcher, select **Settings → Rendering → dgVoodoo2**, then **Direct3D 11** or **Direct3D 12**. The same DLL contains both backends. Linux/Wine lighting support is not qualified.
- Enable Phoenix Lighting in the launcher so it loads when the game starts. Restart the game after changing the output API.
- For a manual update, close the game and back up `config/phoenixlighting`, then replace `plugins/phoenixlighting.dll` with the downloaded DLL. Keep your existing `defaults.ini` and leave `config/phoenixlighting/replacements` empty so the embedded shaders run.
- Version 1.1.5 includes its default profile in the DLL; its ZIP does not include a separate `defaults.ini`.

## Settings

Type `/pl` in game to choose a quality level. **Advanced Settings** exposes common controls; **Debug** or `/pl debug` opens the full settings menu. Use **Save Settings** to keep changes.

This public repository hosts release downloads and release notes. Development is maintained privately.
