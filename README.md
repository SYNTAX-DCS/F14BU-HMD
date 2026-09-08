# F-14B(U) Fictional HMD

A helmet-mounted display for the Heatblur **F-14B(U)** in DCS World. Symbology that follows
your head, so you can find, identify and engage without looking through the HUD.

Heading tape referenced to where you are *looking* · pitch ladder and bank scale · velocity
vector · air contacts with type, range and altitude · ground waypoints and SAM threats ·
weapon status and launch cues · master modes driven by the cockpit DISPLAYS panel.

## Download

Get the latest **installer** and the **user guide (PDF)** from the
[Releases page](../../releases).

## Requirements

- Windows 10 / 11 (64-bit)
- DCS World with the Heatblur **F-14 Tomcat** module (F-14B(U))

## Install

1. Download and run `JHMCS-Installer.exe` from Releases.
2. **Close DCS first**, the mod loads at startup and cannot be replaced while DCS is open.
3. Accept the administrator prompt (only needed if DCS is under `Program Files`).
4. Click **Install**, then start DCS and fly the F-14B(U).

The display appears when you look away from the HUD, and blanks when you look through it.
Full operating instructions are in the user guide (PDF on the Releases page).

## Uninstall

Right-click the tray icon → **Uninstall**. Every file the installer changed is restored
exactly as it was, including any other mod's file it had to move aside.

## If something isn't right

Right-click the tray icon → **Collect Diagnostics**. It writes a zip to your Desktop with
the logs we need. Send it to us on Discord and we can see exactly what the mod is doing.

## Good to know

- **Uses `DCS\bin\version.dll`.** Only one mod can use that slot. If another mod already
  does (for example the Modern F-15E mod, or ReShade), the installer backs it up, tells you
  what it displaced, and restores it when you uninstall, but that mod is inactive while
  this one is installed.
- **The launch cue is an advisory.** DCS does not expose the F-14's weapons computer to
  mods, so the SHOOT cue is computed from range against a per-missile envelope. It tracks
  the HUD closely, but the HUD remains the authority, which is why the cue is drawn dashed.
- **Single-player and immersion focused.** The contact display draws on DCS's world data
  rather than the jet's radar.

## Community & support

Questions, bug reports, feedback, join the [Pixel Pilot Club Discord](https://discord.gg/YJY5XYvCS6).

---

© Pixel Pilot Club. Licensed for personal use; not for redistribution.
