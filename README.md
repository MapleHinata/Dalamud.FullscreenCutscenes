# Ultrawide Cutscenes

A [Dalamud](https://github.com/goatcorp/Dalamud) plugin for Final Fantasy XIV that removes the letterboxing bars displayed during cutscenes on ultrawide monitors, allowing cutscenes to fill your full screen.

> **Note:** Because this expands the rendered viewport beyond the game's intended cutscene boundaries, you may occasionally see things you aren't supposed to — NPCs popping in at the edges, T-poses, scene geometry loading, etc. This is expected behavior and not a bug.

## Requirements

- [Final Fantasy XIV](https://www.finalfantasyxiv.com/)
- [XIVLauncher](https://goatcorp.github.io/) with Dalamud enabled

## Usage

The plugin is active as soon as it's enabled — there's no configuration required. Letterboxing will be removed automatically whenever a cutscene plays.

## Known Limitations

- The expanded viewport may reveal unfinished scene elements at the edges of the screen (NPC pop-in, T-poses, etc.).
- The plugin requires updates when Dalamud's API version changes; if the plugin stops working after a game or Dalamud update, check here for an updated release.

## Credits

- **[goaaats](https://github.com/goaaats/Dalamud.FullscreenCutscenes)** — original plugin author
- **[MapleHinata](https://github.com/MapleHinata/Dalamud.FullscreenCutscenes)** — maintained fork
- **aers** — discovered the underlying technique that makes this possible

## License

This project is licensed under the [AGPL-3.0 License](LICENSE).
