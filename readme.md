<div align="center">
    <h1>Minecraft Client Mods</h1>
    <i>A list with a bunch of Fabric (quilt is reccomeneded) client side mods for minecraft</i>
</div>

<div align="center">
    <h3>Categories</h3>
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#optimisation">Optimisation</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#visual-in-game">Visual (in-game)</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#visual-camera">Visual (camera)</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#audio">Audio</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#gui">GUI</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#hud">HUD</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#utility">Utility</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#customisation">Customisation</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#mcc-island">MCC Island</a> •
    <a href="https://github.com/Imabanana80/Minecraft-Client-Mods#dependencies">Dependencies</a> 
</div>

### Optimisation

| Mod                      | Description                                                                                                | Download                                                              |
| ------------------------ | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| Sodium                   | Designed to improve frame rates and reduce micro-stutter.                                                  | [Github](https://github.com/CaffeineMC/sodium-fabric/releases)        |
| Lithium                  | Speeds up the game whithout sacrificing vanilla functionality.                                             | [Github](https://github.com/CaffeineMC/lithium-fabric/releases)       |
| Phosphor                 | Dramatically improves minecraft's lighting engine. Replaces Starlight.                                     | [Github](https://github.com/CaffeineMC/phosphor-fabric/releases)      |
| Starlight                | Dramatically improves minecraft's lighting engine. Replaces Phosphor and is slightly better.               | [Modrinth](https://modrinth.com/mod/starlight/versions)               |
| Indium                   | Provides Fabric Rendering API support for Sodium and is needed for mods that use Fabric's Rendering API.   | [Github](https://github.com/comp500/Indium/releases)                  |
| SodiumExtra              | Adds additional features that are not, and shouldnt be, in Sodium.                                         | [Github](https://github.com/FlashyReese/sodium-extra-fabric/releases) |
| Krypton                  | Attempts to optimize the Minecraft networking stack. Based on Velocity.                                    | [Github](https://github.com/astei/krypton/releases)                   |
| LazyDFU                  | Makes Minecraft DataFixerUpper initialization lazy. DFU is used when changing minecraft world versions.    | [Github](https://github.com/astei/lazydfu/releases)                   |
| FerriteCore              | Helps reduce ram usage and is more noticable on large modpacks.                                            | [Modrinth](https://modrinth.com/mod/ferrite-core/versions)            |
| Memory Leak Fix          | Fixes random memory leaks. Still a reletively young mod.                                                   | [Modrinth](https://modrinth.com/mod/memoryleakfix/versions)           |
| C2ME                     | Designed to improve the performance of chunk generation, I/O, or loading.                                  | [Github](https://github.com/RelativityMC/C2ME-fabric/releases)        |
| Exordium                 | Renders the HUD and options menues at a lower frame rate.                                                  | [Github](https://github.com/tr7zw/Exordium/releases)                  |
| Enchanced Block Entities | Speeds up Block Entity rendering by using baked block models instead of laggy entity models.               | [Modrinth](https://modrinth.com/mod/ebe/versions)                     |
| ImmediatelyFast          | Speed up immediate mode rendering in Minecraft. A less aggressive replacement for Exordium or EBE.         | [Github](https://github.com/RaphiMC/ImmediatelyFast/releases/)        |
| FastAnim                 | Optimizes calculations in entity animations.                                                               | [Modrinth](https://modrinth.com/mod/fastanim/versions)                |
| FastLoad                 | Modifies the 441 Loading Engine to decrease world loading times.                                           | [Github](https://github.com/BumbleSoftware/Fastload/releases)         |
| Smooth Boot              | Makes minecraft load smoother and possibly faster by editing some parameters related to executors.         | [Github](https://github.com/UltimateBoomer/mc-smoothboot/releases)    |
| Entity Culling           | Uses async path-tracing to hide Tiles/Entities that are not visible. Breaks f3+A trick.                    | [Github](https://github.com/tr7zw/EntityCulling/releases/)            |
| More Culling             | Changes how multiple types of culling are handled in order to improve performance.                         | [Github](https://github.com/fxmorin/MoreCulling/releases)             |
| More Culling Extra       | A few small additions to More Culling.                                                                     | [Github](https://github.com/fxmorin/MoreCullingExtra/releases)        |
| Dynamic FPS              | Limits minecraft's FPS when in the background to improve computer performance.                             | [Modrinth](https://modrinth.com/mod/dynamic-fps/versions)             |
| ForgetMeChunk            | Prevents light map unloads on the client, which eliminates the lag spikes caused by moving between chunks. | [Modrinth](https://modrinth.com/mod/forgetmechunk/versions)           |

### Visual (in-game)

| Mod                 | Description                                                                                                        | Download                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| Iris                | A modern shaders mod intended to be compatible with existing OptiFine shader packs.                                | [Github](https://github.com/IrisShaders/Iris/releases/)                          |
| LambDynamicLights   | A dynamic lights mod for Fabric, like optifine's dynamic lights feature.                                           | [Github](https://github.com/LambdAurora/LambDynamicLights/releases/)             |
| Boosted Brightness  | Allows you to set brightness beyond default levels. aka a fullbright toggle with a hotkey.                         | [Github](https://github.com/adamviola/BoostedBrightness/releases/)               |
| No Fog              | Removes all types of fog                                                                                           | [Modrinth](https://modrinth.com/mod/no_fog/versions)                             |
| Visuality           | A simple client-sided cosmetic mod that will add a bunch of new particles, such as splashes and sparkles           | [Github](https://github.com/PinkGoosik/visuality/releases)                       |
| NotEnoughAnimations | Adds 3rd person animations to way more things, like eating or using a map. Breaks CIT inventory item textures      | [Modrinth](https://modrinth.com/mod/not-enough-animations/versions)              |
| Distant Horizons    | An LOD mod that allows for a massive render distance. Freezes your game when switching dimensions/joining world.   | [Modrinth](https://modrinth.com/mod/distanthorizons/versions)                    |
| Farsight            | Allows you to see further than the server's max render distance.                                                   | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/farsight-fabric/files) |
| Hold That Chunk     | Delays client chunk unloading.                                                                                     | [Modrinth](https://modrinth.com/mod/hold-that-chunk/versions)                    |
| Chunks fade in      | A simple mod that adds a fade-in animation for chunks.                                                             | [Modrinth](https://modrinth.com/mod/chunks-fade-in/versions)                     |
| Kappa               | Adds support for Optifine capes the 'proper' way. Works in snapshots and rarely breaks. Other capes not supported. | [Modrinth](https://modrinth.com/mod/kappa/versions)                              |
| Fabric Capes        | Shows player's Optifine capes with support for other cape mods.                                                    | [Modrinth](https://modrinth.com/mod/capes/versions)                              |
| 3d Skin Layers      | Replaces the usually flat second layer of player skins with a 3d modelled version.                                 | [Github](https://github.com/tr7zw/3d-Skin-Layers/releases)                       |
| TechnoModel         | Makes pigs that are named "Technoblade" have a crown.                                                              | [Github](https://github.com/thecolonel63/technomodel/releases/)                  |

### Visual (camera)

| Mod              | Description                                                                                                          | Download                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| CameraUtils      | Advanced camera altering mod. Adds optifine like zoom, freecam, third person camera customisation and much more.     | [Modrinth](https://modrinth.com/mod/camera-utils/versions)        |
| LogicalZoom      | Super simple optifine zoom fabric replacement.                                                                       | [Github](https://github.com/LogicalGeekBoy/logical_zoom/releases) |
| Zoomify          | Optifine like zoom with scroll wheel control for how zoomed the zoom is.                                             | [Modrinth](https://modrinth.com/mod/zoomify/versions)             |
| BetterHurtCam    | Customise how intense the hurtcam is, or completely disable it. Similar to NoHurtCam                                 | [Modrinth](https://modrinth.com/mod/betterhurtcam/versions/)      |
| Do a Barrel Roll | A fully clientside mod that unlocks elytra camera movement, allowing for full pitch, yaw and roll control in flight. | [Modrinth](https://modrinth.com/mod/do-a-barrel-roll/versions)    |

### Audio

| Mod                      | Description                                                                        | Download                                                               |
| ------------------------ | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| SimpleVoiceChat          | A simple proximity voice chat mod.                                                 | [Modrinth](https://modrinth.com/plugin/simple-voice-chat/versions)     |
| Sound Physics Remastered | Adds realistic sound attenuation, reverberation, and absorption through blocks.    | [Modrinth](https://modrinth.com/mod/sound-physics-remastered/versions) |
| Extra Sounds             | Adds more sounds to the game, like inventory sounds, drop item sounds, and more... | [Modrinth](https://modrinth.com/mod/extrasounds/versions)              |
| Auditory                 | Adds new and unique block sounds.                                                  | [Modrinth](https://modrinth.com/mod/auditory/versions)                 |
| Presence Footsteps       | New and improved footstep sounds with more material sounds.                        | [Github](https://github.com/Sollace/Presence-Footsteps/releases)       |

### GUI

| Mod                | Description                                                                                                             | Download                                                               |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| Mod Menu           | Adds a MODS button like forge to the pause menu, which lists the installed fabric mods, and lets you configure them.    | [Github](https://github.com/TerraformersMC/ModMenu/releases)           |
| Blur               | Blurs the background when in your inventory, a GUI or a menu.                                                           | [Github](https://github.com/Motschen/Blur/releases)                    |
| Xearo's World Map  | Creates a map of the entire area that you have explored.                                                                | [ChocolateMC](https://chocolateminecraft.com/worldmapdownload.php)     |
| MouseWheelie       | Move items quicker around your inventory, sort your inventory, and refill item slots (DISABLE TOTEM REFILL IF CPVPING). | [Github](https://github.com/Siphalor/mouse-wheelie/releases)           |
| Inspecio           | Adds advanced tooltips like shulkerbox tooltips and nbt data.                                                           | [Github](https://github.com/Queerbric/Inspecio/releases)               |
| ShulkerBoxTooltip  | View the contents of shulker boxes from your inventory.                                                                 | [Github](https://github.com/MisterPeModder/ShulkerBoxTooltip/releases) |
| TooltipFix         | Stops tooltips that are too large to fit on the screen from running off the screen.                                     | [Modrinth](https://modrinth.com/mod/tooltipfix/versions)               |
| Smooth Swapping    | Adds a simple slide animation when moving items around in your inventory.                                               | [Modrinth](https://modrinth.com/mod/smooth-swapping/versions)          |
| ItemBorders        | Adds a coloured border to items based on their rarity.                                                                  | [Modrinth](https://modrinth.com/mod/item-borders/versions)             |
| Legendary Tooltips | Makes tooltips fancier, by changing your tooltips into embellished works of art.                                        | [Modrinth](https://modrinth.com/mod/legendary-tooltips/versions)       |
| AdvancementInfo    | Enlarges the advancement menu, and helps keep track of what needs to be done to complete advancements                   | [Modrinth](https://modrinth.com/mod/advancementinfo/versions)          |

### HUD

| Mod                 | Description                                                                                                             | Download                                                                 |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Dynamic Crosshair   | Changes the look of your crosshair based on context.                                                                    | [Modrinth](https://modrinth.com/mod/dynamiccrosshair/versions)           |
| Appleskin           | Adds various food-related HUD improvements, such as a saturation overlay for your hunger bar.                           | [Github](https://github.com/squeek502/AppleSkin/releases)                |
| ArmorChroma         | Different icons in the armor bar depending on the material of the armor.                                                | [Modrinth](https://modrinth.com/mod/armor-chroma-for-fabric/versions)    |
| Totem Counter       | Shows the amount of totem pops for every player above their nametag, and shows totems you have.                         | [Modrinth](https://modrinth.com/mod/totemcounter/versions)               |
| Numeral Ping        | Display's each player's ping in the tab menu, and replaces the connection bars. Does not work properly on some servers. | [Modrinth](https://modrinth.com/mod/numeral-ping/versions)               |
| BetterPingDisplay   | Display's each player's ping in the tab menu. Does not work properly on some servers such as MCC-Island.                | [Modrinth](https://modrinth.com/mod/better-ping-display-fabric/versions) |
| BetterF3            | Improves and allows the customisation of the F3 menu.                                                                   | [Github](https://github.com/cominixo/BetterF3/releases)                  |
| Ugly Scoreboard Fix | Offers multiple scoreboard modifications to optimize the look of the sidebar in your game. (Removes numbers)            | [Modrinth](https://modrinth.com/mod/ugly-scoreboard-fix/versions)        |
| Status Effect Bars  | Adds a bar to status effects to show remaining duration of effects.                                                     | [Modrinth](https://modrinth.com/mod/status-effect-bars/versions)         |
| Xearo's Minimap     | Because minecraft should have a minimap.                                                                                | [ChocolateMC](https://chocolateminecraft.com/minimapdownload.php)        |

### Utility

| Mod                     | Description                                                                                                           | Download                                                                    |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Tweakaroo               | Adds a whole bunch of various different "tweaks" to the game, like better block placement or a built in autoclicker.  | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/tweakeroo/files)  |
| Minihud                 | Adds a whole bunch of useful overlays to the game.                                                                    | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/minihud/files)    |
| Better PVP              | Includes xearo's minimap and adds many pvp inproving client side changes, like potion display or health display.      | [ChocolateMC](https://chocolateminecraft.com/betterpvpdownload.php)         |
| NoChatReports           | Strips cryptographic signatures that since 1.19 are attached to every message sent in the chat.                       | [Modrinth](https://modrinth.com/mod/no-chat-reports/versions)               |
| Via-Fabric              | Allows the client to connect to servers that are on an older version.                                                 | [Modrinth](https://modrinth.com/mod/viafabric/versions)                     |
| Multiconnect            | Allows the client to connect to servers that are on an older version.                                                 | [Github](https://github.com/Earthcomputer/multiconnect/releases)            |
| Litematica              | A modern schematic mod.                                                                                               | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/litematica/files) |
| Replay Mod              | Allows you to create and render cinamatic clips and videos.                                                           | [Website](https://www.replaymod.com/download/)                              |
| Isometric Renders       | Render high-resolution isometric screenshots of builds, items and blocks.                                             | [Modrinth](https://modrinth.com/mod/isometric-renders/versions)             |
| Shared Resources        | Easily share game files between separate Minecraft instances.                                                         | [Modrinth](https://modrinth.com/mod/shared-resources/versions)              |
| Reese's Sodium Options  | Alternative Options Menu for Sodium.                                                                                  | [Modrinth](https://modrinth.com/mod/reeses-sodium-options/versions)         |
| EasierVillagerTrading   | Trade with villagers faster and more easily.                                                                          | [Modrinth](https://modrinth.com/mod/easiervillagertrading/versions)         |
| Better Recipe Book      | Adds a 'few' quality of life changes to the recipe book.                                                              | [Modrinth](https://modrinth.com/mod/brb/versions)                           |
| Fabrishot               | Take insanely high resolution (4k) screenshots.                                                                       | [Github](https://github.com/ramidzkh/fabrishot/releases)                    |
| Screenshot to Clipboard | Automatically copies a taken screenshot to your clipboard, which allows you to quickly and easily share a screenshot. | [Modrinth](https://modrinth.com/mod/screenshot-to-clipboard/versions)       |
| Quick Elytra            | Switch your chestplate and elytra with a keybind.                                                                     | [Modrinth](https://modrinth.com/mod/quick-elytra/versions)                  |
| Time to Live            | Adds a timer to TNT and Creepers before they explode.                                                                 | [Modrinth](https://modrinth.com/mod/timetolive/versions)                    |

### Customisation

| Mod                | Description                                                                                                              | Download                                                                |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| CIT Resewn         | Adds MCPatcher's and Optifine's CIT (custom item textures) support for resource packs.                                   | [Modrinth](https://modrinth.com/mod/cit-resewn/versions)                |
| Chime              | Adds MCPatcher's and Optifine's CIT (custom item textures) support but with a DIFFERENT CIT FORMAT. Replaces CIT Resewn. | [Github](https://github.com/emilyploszaj/chime/releases/)               |
| Animatica          | Adds MCPatcher's and Optifine's animated texture format support for resource packs.                                      | [Modrinth](https://modrinth.com/mod/animatica/versions)                 |
| Colormatic         | Allows resource packs to customize hard coded colors in game. Similar to Optifine's custom color feature.                | [Modrinth](https://modrinth.com/mod/colormatic/versions)                |
| Continuity         | Adds support for MCPatcher's and Optifine's connected textures and emmisive textures.                                    | [Github](https://github.com/PepperCode1/Continuity/releases/)           |
| CEM                | Custom Entity Models is an implementation of custom entity models heavily based off of Optifine's format.                | [Modrinth](https://modrinth.com/mod/cem/versions)                       |
| ETF                | Entity Texture Features adds randomized & emissive texture support for mobs set by the resourcepack.                     | [Github](https://github.com/Traben-0/Entity_Texture_Features/releases/) |
| FabricSkyboxes     | Custom skyboxes mod for Fabric. Optifine format not supported.                                                           | [Github](https://github.com/AMereBagatelle/fabricskyboxes/releases/)    |
| OptiGUI            | A mod allowing to animate GUI textures or replace container textures with minimal predicates.                            | [Modrinth](https://modrinth.com/mod/optigui/versions)                   |
| ServerPackUnlocker | Gives Server Resource Packs vanilla-ish behavior.                                                                        | [Modrinth](https://modrinth.com/mod/server-pack-unlocker/versions)      |

### MCC Island

| Mod              | Description                                                                                                         | Download                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Noxesium         | An OPTIMISATION mod developed by noxcrew specificly for MCC Island, and fixing bugs specific to MCCI.               | [Modrinth](https://modrinth.com/mod/noxesium/versions)            |
| MCCI Utils       | A utility mod for MCC Island. Adds Discord RP, friend notifs, and much more.                                        | [Modrinth](https://modrinth.com/mod/mcci-utils/versions)          |
| Island Utils     | Another utility mod for MCC Island. Adds Discord RP, chat buttons, and game music.                                  | [Github](https://github.com/AsoDesu/IslandUtils/releases)         |
| MCCI: Companion  | Another utility mod for MCC Island. Converts many chat messages into popups, adds Discord RP, music, but no config. | [Modrinth](https://modrinth.com/mod/mccic/versions)               |
| Island Champ     | Another utility mod for MCC Island. Adds special keybinds and a seprate chat channel for PMs.                       | [Modrinth](https://modrinth.com/mod/island-champ/versions)        |
| Island Menu      | Makes the title screen MCCI themed.                                                                                 | [Github](https://github.com/MoSadie/Island-Menu/releases)         |
| MCCI Nametag Mod | Displays your own nametag for yourself exactly how it looks for other people.                                       | [Github](https://github.com/anastarawneh/MCCINametagMod/releases) |

##### Many MCC Island util mods are still in development and all have amazing features planned, but are currently still quite bare-bones. As of now, i reccomend using MCCI Utils if you are fine without music and Island Utils if you want music. Please feel free to try any and even all of them out, as they all have slightly different features.

### Dependencies

| Mod                      | Description                                                                                        | Download                                                               |
| ------------------------ | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| Fabric API               | Library with essential hooks and interoperability mechanisms for Fabric mods.                      | [Github](https://github.com/FabricMC/fabric/releases)                  |
| Quilted Fabric API + QSL | Essential standard libraries for the Quilt ecosystem.                                              | [Modrinth](https://modrinth.com/mod/qsl/versions)                      |
| Fabric Language Kotlin   | Fabric language module for Kotlin.                                                                 | [Modrinth](https://modrinth.com/mod/fabric-language-kotlin/versions)   |
| Cloth Config API         | A simple configuration library for fabric mods.                                                    | [Modrinth](https://modrinth.com/mod/cloth-config/versions)             |
| CompleteConfig           | Another configuration library for fabric mods.                                                     | [Modrinth](https://modrinth.com/mod/completeconfig/versions)           |
| YetAnotherConfigLib      | Another configuration library for fabric mods.                                                     | [Modrinth](https://modrinth.com/mod/yacl/versions)                     |
| MaLiLib                  | a library mod containing shared code for masa's client-side mods. Needed for tweakaroo and minihud | [Modrinth](https://www.curseforge.com/minecraft/mc-mods/malilib/files) |
| ukulib                   | Small utility library used, and made for uku3lig's mods.                                           | [Modrinth](https://modrinth.com/mod/ukulib/versions)                   |
| oωo lib                  | Used by isometric renders mod.                                                                     | [Modrinth](https://modrinth.com/mod/owo-lib/versions)                  |

#### If you are having trouble navigating the GITHUB download page, or the versions are not updated/listed properly, please open an issue, or convert it to modrinth, then create a pull request.
