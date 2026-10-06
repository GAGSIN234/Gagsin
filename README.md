# Gun Mod (Fabric 1.21.11)

Six guns, each with its own damage, recipe, craftable magazine and reload style.

- Right-click: shoot. Empty gun + right-click: reload (uses one of that gun's magazines from your inventory; free in creative).
- Sneak + right-click: inspect (stats, loaded ammo, magazine type). Hover the item for stats too.
- Switching away from a gun mid-reload cancels it and returns the magazine.

## Build the .jar
Option A (no setup): upload this folder to a GitHub repo, open the Actions tab, run "build", download the `gunmod-jar` artifact.
Option B (local): install JDK 21 + Gradle 9.2+, then run `gradle build`. The jar is `build/libs/gunmod-1.0.0.jar`.
Put the jar in `mods/` together with Fabric API for 1.21.11.

If the build prints a compile error, copy it back to Claude and it will be fixed.
