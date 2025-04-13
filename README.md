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

### Required Mods
- Architectury [6.6.92]
- AudioPlayer [1.19.2-1.8.9]
- Automobility [0.4.2+1.19.2-fabric]
- BadOptimizations [2.1.4]
- BlossomLib [2.5.1+1.19]
- BlossomWarps [2.0.4+1.19]
- Concurrent Chunk Management Engine [0.2.0+alpha.9.11]
- Dynamic FPS [3.7.3]
- Dynamic Sound Filters [1.3.0+1.19]
- Easy Authentication [3.1.8]
- Enhanced Block Entities [0.7.2+1.19.2]
- EntityCulling [1.6.1-mc1.19.2]
- Fabric API [0.77.0+1.19.2]
- Fabric Language Kotlin [1.12.2+kotlin.2.0.20]
- Fabric Tree Chopper [0.8.10]
- FerriteCore [5.0.3]
- ImmediatelyFast [1.2.21+1.19.2]
- Indium [1.0.9+mc1.19.2]
- Iris [1.6.11]
- Joban Client [1.2.1-hotfix-1+mc1.19.2]
- LazyDFU [0.1.3]
- Lithium [0.11.1]
- MTR London Underground [1.19.2-3.2.0-2.0.7]
- MTR Russian Metro [1.19.2-3.2.2-1.0.0]
- MTR Station Decoration [1.19.2-3.2.2-1.3.4]
- Minecraft Transit Railway [1.19.2-3.2.2-hotfix-1]
- ModernFix [5.18.0+mc1.19.2]
- More Culling [1.19.1-0.17.0]
- Nemo's Transit Expansion [0.5.2+1.19.2]
- Reese's Sodium Options [1.6.4+mc1.19.2]
- Resourcify [1.4.2]
- Slideshow [1.19.2-1.0.2]
- Smooth Boot [1.19-1.7.1]
- Sodium [0.4.4+build.18]
- Sodium Extra [0.4.16+mc1.19.2]
- Starlight [1.1.1+fabric.ae22326]
- Terralith [1.0]
- TransitManager [1.3.0+mc1.19.2]
- Very Many Players [0.2.0+beta.7.30]
- Visual PIDS Editor [1.0.3]
- WorldEdit [7.2.11]
- Xaero's Minimap [23.7.0]
- Xaero's World Map [1.30.5]
- YetAnotherConfigLib [2.2.0]
- spark [1.10.37]
- squaremap [1.1.8]

### Optional Mods
- Simple Voice Chat [1.19.2-2.5.26]
- Carpet [1.19.2-1.4.84]
- Continuity [2.0.2+1.19]
- WorldEdit CUI [1.19.2+01]
- Visible Barriers [1.5.3+1.19.x]
- Zoomify [2.9.0]
