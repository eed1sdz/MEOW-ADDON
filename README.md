# Meow (Meteor Client addon, Minecraft 1.21.11)

## Categories and modules

**Meow**
- `custom-fov` – custom field of view
- `custom-crosshair` – configurable crosshair (cross / T / X / dot / circle, attack-cooldown bar)
- `block-overlay` – animated outline + fill on the targeted block, mining progress
- `custom-glint` – recolours the enchantment glint

**Meow 2**
- `hole-esp` – holes, 3x1 holes, tunnels, staircases
- `chunk-scanner` – marks chunks with suspicious stone stacks

## Build

```
./gradlew build
```

The jar is in `build/libs/`. Put it in `mods/` next to Meteor Client 1.21.11.

If the Gradle wrapper is missing, copy `gradlew`, `gradlew.bat` and `gradle/wrapper/` from your
existing 1.21.11 addon project (or from meteor-addon-template), and if the build files differ
(Loom / loader / Meteor versions), keep the versions from that working project.
