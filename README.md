# Minecraft Modpack Project

This project contains a Minecraft modpack created using packwiz, designed for Prism Launcher.

## Project Structure
- `pack.toml`: Main packwiz configuration file
- `mods/`: Directory containing all mod configurations
- `index.toml`: Index of all mods and files in the pack
- `optional-mods/`: Directory containing optional mod configurations
- `resourcepacks/`: Resource packs for the modpack
- `bootstrap/`: Contains the auto-update configuration

## Optional Mods
The following mods are optional and can be installed based on your preference:
- Simple Voice Chat: For voice communication
- Carpet: For advanced game mechanics and debugging
- Continuity: For connected textures
- WorldEdit CUI: For WorldEdit visualization
- Visible Barriers: For seeing barrier blocks
- Zoomify: For zoom functionality

## Installation for Prism Launcher
1. Create a new 1.19.2 Fabric instance in Prism Launcher
2. Copy the `packwiz-installer-bootstrap.jar` from the `bootstrap` folder to your instance's `mods` folder
3. Copy `packwiz-url.txt` to your instance folder (same level as the mods folder)
4. Launch the game - the bootstrap will automatically download and install all required mods
5. Optional mods can be installed from the `optional-mods` folder based on your needs

## Auto-Updates
This modpack uses packwiz for automatic updates. When you launch the game:
1. The bootstrap mod will check for updates
2. If updates are available, they will be automatically downloaded
3. All mods are pinned to specific versions for stability
4. Updates will only occur when new versions are pushed to this repository

## Mod List
All mods are pinned to specific versions:
[List of mods will be auto-generated]
