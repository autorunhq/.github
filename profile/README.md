<p align="center">
  <img src="https://raw.githubusercontent.com/autorunhq/autorun/main/documentation/logo-image.png" alt="Autorun logo" width="180">
</p>

<h1 align="center">Autorun</h1>

<p align="center">Play Windows PC games on your Nintendo Switch.</p>

Autorun is a homebrew app that runs Windows games and programs on the Switch.
It brings [Wine](https://www.winehq.org) to the Switch's own operating system,
Horizon, and translates PC (x86 and x64) code for the Switch's ARM processor with
[FEX](https://github.com/FEX-Emu/FEX) and [Box64](https://github.com/ptitSeb/box64).
Games draw through Mesa's OpenGL and NVK Vulkan, with DXVK and VKD3D-Proton for
Direct3D. You bring the games: copy your own PC copies to the SD card and start
them from Autorun's library.

<p align="center">
  <img src="https://raw.githubusercontent.com/autorunhq/autorun/main/documentation/launcher.jpg" alt="The Autorun launcher" width="640">
</p>

## Repositories

| | |
|---|---|
| [**autorun**](https://github.com/autorunhq/autorun) | The app: Wine for Horizon, the launcher, the CPU translation and graphics. [Download the latest release](https://github.com/autorunhq/autorun/releases/latest) and see what runs. |
| [**autorun-horizon-dlls**](https://github.com/autorunhq/autorun-horizon-dlls) | Every Windows DLL Autorun runs, built from Wine and laid out as on the SD card. The app downloads and updates them itself. |
| [**switch-dev**](https://github.com/autorunhq/switch-dev) | The Docker image Autorun is built in: devkitA64 with libnx, mesa-switch, LSFG-VK and libusbhsfs for Horizon. Usable for any Switch homebrew. |

Autorun is experimental. Some games run well, and many start and then stop on
something that isn't done yet. Every run writes a log that says where. Reports
with that log are welcome in [Autorun's issues](https://github.com/autorunhq/autorun/issues).
