# F-14B(U) Fictional HMD

A helmet-mounted display for the Heatblur **F-14B(U)** in DCS World. Symbology that follows
your head, so you can find, identify and engage without looking through the HUD.

Heading tape referenced to where you are *looking* · pitch ladder and bank scale · velocity
vector · air contacts with type, range and altitude · your radar's lock, marked with the
HUD's own box · look-and-lock on a DCS bind · ground waypoints and SAM threats ·
weapon status and launch cues · master modes driven by the cockpit DISPLAYS panel.

## Download

Get the latest **installer** and the **user guide (PDF)** from the
[Releases page](../../releases).

## Requirements

- Windows 10 / 11 (64-bit)
- DCS World with the Heatblur **F-14 Tomcat** module (F-14B(U))

## Install

1. Download and run `HMD-Installer.exe` from Releases.
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

- **Uses `DCS\bin\version.dll`.** Only one mod can use that slot. If another mod or tool
  already uses it (ReShade, for example), the installer backs it up, tells you what it
  displaced, and restores it when you uninstall, but that one is inactive while this one is
  installed.
- **The launch cue is an advisory.** DCS does not expose the F-14's weapons computer to
  mods, so SHOOT is worked out by the mod: your radar has the target locked and he is inside
  the selected missile's maximum range. It sits just above the lock box, where your HUD puts
  it. It tracks the HUD closely, but the HUD remains the authority.
- **Contacts follow your radar.** An aircraft appears in the helmet only while your radar is
  transmitting and he is inside the volume it is scanning. It is not a radar simulation: DCS
  does not tell mods what the real radar has lost to the notch, chaff or jamming, so the TID
  remains the authority.
- **Helmet lock is always installed.** Look at an aircraft and press your helmet lock
  button, and your radar locks the first aircraft in a small patch of sky centred where you
  are looking, out to about 80 NM on a fighter. You get LOCKING while it works, then LOCKED
  with the target drawn as a square with four short lines off its corners, like your HUD, and
  SHOOT above it once he is in range. A target past 5 NM gets up to five seconds for the radar
  to find him. Inside 5 NM there is also a second try on the pulse lock, for the tail chase of
  a guns fight.
- **Bind it in DCS.** Options > Controls, pick **F-14B(U) HMD** in the aircraft list,
  category **HMD**, **Helmet Lock (look and lock)**. It is Page Up by default: put it on your
  HOTAS. Your numpad view keys never fire it.
- **It works the back-seat radar for you.** It presses the back-seat radar controls and
  pauses Jester while it works, and it cannot tell Jester from a person. With a human RIO in
  the back, agree it with them before you use it. While a missile you fired is still guiding
  on the lock, the helmet shows MSL GUIDING and will not try, so the lock is not dropped
  under it.

## Community & support

Questions, bug reports, feedback, join the [Pixel Pilot Club Discord](https://discord.gg/YJY5XYvCS6).

---

© Pixel Pilot Club. Licensed for personal use; not for redistribution.
