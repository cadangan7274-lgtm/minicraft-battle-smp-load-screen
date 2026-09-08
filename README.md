# Minicraft Battle SMP — Animated Title Screen

Target: Minecraft Java 1.21.11 + Fabric Loader 0.18+ + Java 21.

## What it does
- Replaces the vanilla title-screen background.
- Uses the included 1920x1080 `title_background.png`.
- Adds lightweight animation:
  - drifting dark cloud bands
  - moving water shimmer
  - floating red embers
  - subtle red atmospheric pulse
  - dark vignette
- slow camera/background parallax
- tiny mouse-reactive camera movement
- Client-side only; it does not change gameplay or server behavior.

## Build
Install Java 21 and use a Gradle installation or a Gradle wrapper generated from the project.

Run:
    gradle build

The remapped JAR will be in:
    build/libs/

Copy the non-dev JAR into:
    .minecraft/mods/

For PojavLauncher, put the JAR into the instance's `mods` folder.

## Important
This source package is intentionally kept lightweight for Android/Pojav. The visual animation is rendered procedurally over the static background rather than using a heavy shader.
