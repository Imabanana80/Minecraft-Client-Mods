# Minecraft Client Mods

This is a simple repo with a bunch of FABRIC client side mods for minecraft

## Optimisation

| Mod                      | Description                                                                                                        | Download                                                              |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| Sodium                   | Designed toimprove frame rates and reduce micro-stutter.                                                           | [Github](https://github.com/CaffeineMC/sodium-fabric/releases)        |
| Lithium                  | Speeds up the game whithout sacrificing vanilla functionality.                                                     | [Github](https://github.com/CaffeineMC/lithium-fabric/releases)       |
| Phosphor                 | Dramatically improves minecraft's lighting engine. Replaces Starlight.                                             | [Github](https://github.com/CaffeineMC/phosphor-fabric/releases)      |
| Starlight                | Dramatically improves minecraft's lighting engine. Replaces Phosphor and is slightly better.                       | [Modrinth](https://modrinth.com/mod/starlight/versions)               |
| Indium                   | Provides Fabric Rendering API support for Sodium and is required for mods that use Fabric's Rendering API.         | [Github](https://github.com/comp500/Indium/releases)                  |
| SodiumExtra              | Adds additional features that are not, and shouldnt be, in Sodium.                                                 | [Github](https://github.com/FlashyReese/sodium-extra-fabric/releases) |
| Krypton                  | Attempts to optimize the Minecraft networking stack. Based on Velocity.                                            | [Github](https://github.com/astei/krypton/releases)                   |
| LazyDFU                  | Makes Minecraft DataFixerUpper initialization lazy. DataFixerUpper is used when changing minecraft world versions. | [Github](https://github.com/astei/lazydfu/releases)                   |
| FerriteCore              | Helps reduce ram usage and is more noticable on large modpacks.                                                    | [Modrinth](https://modrinth.com/mod/ferrite-core/versions)            |
| Memory Leak Fix          | Fixes random memory leaks. Still a reletively young mod.                                                           | [Github](https://github.com/fxmorin/MemoryLeakFix/releases/)          |
| C2ME                     | Designed to improve the performance of chunk generation, I/O, and loading. Takes advantage of multiple CPU cores.  | [Github](https://github.com/RelativityMC/C2ME-fabric/releases)        |
| Exordium                 | Renders the HUD and options menues at a lower frame rate.                                                          | [Github](https://github.com/tr7zw/Exordium/releases)                  |
| Enchanced Block Entities | Speeds up Block Entity rendering by using baked block models instead of laggy entity models.                       | [Modrinth](https://modrinth.com/mod/ebe/versions)                     |
| ImmediatelyFast          | Speed up immediate mode rendering in Minecraft. A less aggressive replacement for Exordium or EBE.                 | [Github](https://github.com/RaphiMC/ImmediatelyFast/releases/)        |
| FastLoad                 | Modifies the 441 Loading Engine to decrease world loading times.                                                   | [Github](https://github.com/BumbleSoftware/Fastload/releases)         |
| Smooth Boot              | Makes minecraft load smoother and possibly faster by editing some parameters related to executors.                 | [Github](https://github.com/UltimateBoomer/mc-smoothboot/releases)    |
| Entity Culling           | Uses async path-tracing to hide Tiles/Entities that are not visible. Breaks f3+A trick and is not configurable.    | [Github](https://github.com/tr7zw/EntityCulling/releases/)            |
| More Culling             | Changes how multiple types of culling are handled in order to improve performance.                                 | [Github](https://github.com/fxmorin/MoreCulling/releases)             |
| More Culling Extra       | A few small additions to More Culling.                                                                             | [Github](https://github.com/fxmorin/MoreCullingExtra/releases)        |
| Dynamic FPS              | Limits minecraft's FPS when in the background to improve computer performance.                                     | [Modrinth](https://modrinth.com/mod/dynamic-fps/versions)             |
