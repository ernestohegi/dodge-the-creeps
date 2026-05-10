# Dodge the creeps!

A small arcade-style 2D game built with Godot where you move a player character, avoid enemies, and survive as long as possible while your score increases over time.

## Project Details

- Engine: Godot 4.x (`config/features` includes `4.6`)
- Main scene: `main.tscn`
- Window size: `480 x 720`

## How to Run

### Option 1: Run from the Godot Editor

1. Open Godot.
2. Click **Import** and select this project's `project.godot` file.
3. Open the project.
4. Press **Play** (or `F5`) to run the main scene.

### Option 2: Run from CLI

If Godot is installed and available in your PATH:

```bash
godot4 --path .
```

If your binary is named differently on your system (for example `godot`), use that command instead.

## Controls

- Move: Arrow keys (`Up`, `Down`, `Left`, `Right`)
- Start game action: `Enter`

## Project Structure

- `project.godot`: project configuration
- `main.tscn` / `main.gd`: main scene and game flow
- `player.tscn` / `player.gd`: player scene and movement logic
- `mob.tscn` / `mob.gd`: enemy scene and behavior
- `art/`: sprites and audio assets
- `fonts/`: font files and licenses

## Godot Links

- Godot website: https://godotengine.org/
- Download Godot: https://godotengine.org/download
- Official docs: https://docs.godotengine.org/
- Getting started (2D): https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html

## License

No project-specific license file is currently included in this repository.
