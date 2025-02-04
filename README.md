<div align="center">
  <!-- Logo and Title -->
  <img src="/src/main/resources/assets/rejects/icon.png" alt="logo" width="20%"/>
  <h1>Meteor Rejects</h1>
  <p>An addon to Meteor Client that adds modules and commands that were too useless to be added to Meteor directly.</p>

  <!-- Fancy badges -->
  <a href="https://anticope.ml/pages/MeteorAddons.html"><img src="https://img.shields.io/badge/Verified%20Addon-Yes-blueviolet" alt="Verified Addon"></a>
  <a href="https://github.com/AntiCope/meteor-rejects/releases"><img src="https://img.shields.io/badge/Version-v0.1-orange" alt="Version"></a>
  <img src="https://img.shields.io/badge/spaghetti%20code-yes-success?logo=java" alt="Spagetti code: yes">
  <img src="https://img.shields.io/badge/Minecraft%20Version-1.18-blue" alt="Minecraft Version">
  <a href="https://github.com/AntiCope/meteor-rejects/commits/master"><img src="https://img.shields.io/github/last-commit/AntiCope/meteor-rejects?logo=git" alt="Last commit"></a>
  <img src="https://img.shields.io/github/workflow/status/AntiCope/meteor-rejects/Java%20CI%20with%20Gradle?logo=github" alt="build status">
  <img src="https://img.shields.io/github/languages/code-size/AntiCope/meteor-rejects" alt="Code Size">
  <img src="https://img.shields.io/github/repo-size/AntiCope/meteor-rejects" alt="Repo Size">
  <img src="https://img.shields.io/github/issues/AntiCope/meteor-rejects" alt="Issues">
  <img src="https://img.shields.io/github/stars/AntiCope/meteor-rejects" alt="Stars">

  <!-- Popbobob -->
  <img src="https://user-images.githubusercontent.com/18114966/132936934-80658aee-79a7-44cf-ba7b-45386a944c01.png" width="250"><sub><a href="#popbob">*</a></sub>
</div>

# How to use
-fuck u m8

# Features
## Modules
- AntiBot (Removed from Meteor in [166fc](https://github.com/MeteorDevelopment/meteor-client/commit/166fccc73e53de6cfdbe41ea58dc593a2f5011f6#diff-05896d5a7f735a14ee8da5d12fbd24585862ca68efdf32b9401b3f4329d17c73))
- AntiSpawnpoint
- AntiVanish
- Auto32K (Removed from Meteor in [67f93](https://github.com/MeteorDevelopment/meteor-client/commit/67f93de1e5e287ea62ddef041441306f01249c3d#diff-95d3e3b18ffadf76eef2358f30d424843d57acf8bde5ebd49a3f6befa6ff0529))
- AutoBedTrap (Ported from [BleachHack-CupEdition](https://github.com/CUPZYY/BleachHack-CupEdition/blob/master/CupEdition-1.17/src/main/java/bleach/hack/module/mods/AutoBedtrap.java))
- AutoCraft (More generalized version of [AutoBedCraft](https://github.com/GhostTypes/orion/blob/main/src/main/java/me/ghosttypes/orion/modules/main/AutoBedCraft.java) from orion)
- AutoExtinguish
- AutoEz
- AutoPot (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/274))
- AutoTNT
- AutoWither (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1070))
- BlockIn
- BoatGlitch & BoatPhase (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/814))
- Boost (Ported from [Cornos](https://github.com/cornos/Cornos/blob/master/src/main/java/me/zeroX150/cornos/features/module/impl/movement/Boost.java))
- ColorSigns
- Confuse
- Coord Logger (World events from [JexClient](https://github.com/DustinRepo/JexClient-main/blob/main/src/main/java/me/dustin/jex/feature/mod/impl/misc/CoordFinder.java))
- Custom Packets
- Ghost Mode (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1932))
- InteractionMenu (Ported from [BleachHack](https://github.com/BleachDrinker420/BleachHack/pull/211))
- Lavacast
- NewChunks (Ported from [BleackHack](https://github.com/BleachDrinker420/BleachHack/blob/master/BleachHack-Fabric-1.17/src/main/java/bleach/hack/module/mods/NewChunks.java))
- ObsidianFarm (Taken from [Meteor ObsidianFarm Addon](https://github.com/VoidCyborg/meteor-obsidian-farm))
- Oresim (Ported from [Atomic](https://gitlab.com/0x151/atomic))
- PacketFly (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/813))
- Painter
- Prone (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1423))
- Rendering
- SkeletonESP (Ported from [JexClient](https://github.com/DustinRepo/JexClient-main/blob/main/src/main/java/me/dustin/jex/feature/mod/impl/render/Skeletons.java))
- SoundLocator

### Modifications
- NoRender
  - `noCommandSuggestions` (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1347))
- Flight
  - `stopMomentum`

## Commands
- `.center`
- `.clear-chat` (Removed from meteor in [9aebf](https://github.com/MeteorDevelopment/meteor-client/commit/9aebf6a0e4ffa739d901c8b8d7f48d07af2fe839))
- `.ghost` (Ported from [AntiGhost](https://github.com/gbl/AntiGhost/blob/fabric_1_16/src/main/java/de/guntram/mcmod/antighost/AntiGhost.java))
- `.save-skin`
- `.heads`
- `.seed` (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1300))
- `.setblock`
- `.panic` (Removed from meteor in [dd5f8](https://github.com/MeteorDevelopment/meteor-client/commit/dd5f88a0dbb2753372bf37c58461b886104dc990))
- `.set-velocity`
- `.teleport`
- `.terrain-export` (Ported from [BleachHack](https://github.com/BleachDrinker420/BleachHack/blob/master/BleachHack-Fabric-1.17/src/main/java/bleach/hack/command/commands/CmdTerrain.java))
- `.kick` (Ported from [LiquidBounce](https://github.com/CCBlueX/LiquidBounce/blob/nextgen/src/main/kotlin/net/ccbluex/liquidbounce/features/module/modules/exploit/ModuleKick.kt))

### Modifications
- `.server`
  - `ports` (Ported from [Cornos](https://github.com/cornos/Cornos/blob/master/src/main/java/me/zeroX150/cornos/features/command/impl/Scan.java))
- `.locate`
  - rewrite (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/1300))
- `.give`
  - presets (Some presets were taken from [BleachHack](https://github.com/BleachDrinker420/BleachHack/blob/master/BleachHack-Fabric-1.17/src/main/java/bleach/hack/command/commands/CmdGive.java))

## Themes
- "Meteor Rounded" theme (Taken from an [unmerged PR](https://github.com/MeteorDevelopment/meteor-client/pull/619))

## HUD
- Baritone process HUD
- CPS HUD (Ported from [AuroraKeystrokes](https://github.com/LambdAurora/AuroraKeystrokes/tree/1.16/src/main/java/me/lambdaurora/keystrokes))

## Config
- `Http Allowed` - modify what http requests can be made with Meteor's http api
- `Hidden Modules` - hide modules from module gui. **requires restart when unhiding**

<sub>
<a name="popbob" id="popbob" href="#popbob">*</a> this statement is not true at all, popbob never approved of this
</sub>
