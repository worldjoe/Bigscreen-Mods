# Bigscreen Mods

Unofficial community mods for Bigscreen PC VR. These projects are not
affiliated with Bigscreen, Inc.

## Mods

| Mod | What it does | Download |
| --- | --- | --- |
| [Bigscreen Passthrough](https://github.com/worldjoe/BigscreenPassthrough) | Applies a chroma background for Virtual Desktop VR Passthrough. | [Latest release](https://github.com/worldjoe/BigscreenPassthrough/releases/latest) |
| [Bigscreen Multi 3D](https://github.com/worldjoe/BigscreenMulti3d) | Sets 2D, side-by-side, or over-under independently for personal monitors 2 and 3. | [Latest release](https://github.com/worldjoe/BigscreenMulti3d/releases/latest) |
| [Bigscreen Screen Grab](https://github.com/worldjoe/BigscreenScreenGrab) | Moves and resizes the main screen; includes Cam 2 follow for streaming. | [Latest release](https://github.com/worldjoe/BigscreenScreenGrab/releases/latest) |
| [Bigscreen Moderator Alerts](https://github.com/worldjoe/BigscreenModeratorAlerts) | Provides speaking-activity alerts and block-list backup tools. | [Latest release](https://github.com/worldjoe/BigscreenModeratorAlerts/releases/latest) |

### Developer tool

[Bigscreen Scene Probe](https://github.com/worldjoe/BigscreenSceneProbe) is a
diagnostic tool for developers, **not recommended for normal use**. Gathering
diagnostics can needlessly slow down Bigscreen. Its captures can contain
user-identifying information; review them before sharing.
[Latest release](https://github.com/worldjoe/BigscreenSceneProbe/releases/latest)

## Getting started

1. Install [MelonLoader](https://github.com/LavaGang/MelonLoader) for Bigscreen.
   IL2CPP games require the .NET 6 Desktop Runtime.
2. Read the mod's README and release notes for dependencies, compatibility,
   controls, and limitations. Some menu toggles require Bigscreen Behind.
3. Download the mod DLL from its release, close Bigscreen, and copy the DLL into
   the game's `Mods` folder. Remove the DLL while Bigscreen is closed to
   uninstall.

Mods depend on game internals and may stop working after updates. Do not copy
game dependency DLLs into `Mods`.

**Important:** Moderator Alerts' block-list import is untested and may cause
account problems. Screen Grab's Cam 2 follow is not a privacy guarantee: inspect
the desktop feed before every stream. Read the individual project documentation
before using either feature.
