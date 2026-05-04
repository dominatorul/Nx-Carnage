# NX-Carnage
Lightweight custom firmware pack for overclocking enthusiasts.

> [!NOTE]
> This project is developed for informational purposes, showcasing the capabilities of Switch hardware, and is not aimed at extracting commercial benefits.

> [!WARNING]
> Overclocking the console does not lead to irreversible hardware damage, however it poses a risk to data due to the nature of Horizon OS. It is strongly recommended to use overclocking exclusively in emuMMC and to make regular backups. **USE AT YOUR OWN RISK!**

## Community & Support
- Discord: [Horizon OC](https://dsc.gg/horizonoc)
- Discord: [NSwitch 60FPS Cheats & Mods](https://discord.com/invite/UqN6FcepTQ) — `#overclocking`

---

## Installation

1. Make a backup and delete everything except the `Nintendo` and `emuMMC` folders from your SD card.
2. Unpack [NX-Carnage]( ) to the root of the SD card via a card reader, or through `Hekate` → `Tools` → `USB Tools`.
3. Use the `Easy Setup` package to continue installation.

---

## Usage

1. **Launch Ultrahand** by pressing `ZL + ZR + DPAD DOWN` simultaneously. Press `DPAD RIGHT`, open `Easy Setup Installer`, and select `Install Easy Setup`.

   > [!NOTE]
   > Make sure you have a working internet connection and that your system time is set correctly, otherwise the process may fail.

2. Once the download is complete, **restart Ultrahand** by pressing `B` twice to exit, then relaunch it. Press `DPAD RIGHT` — if successful, the package name will update and the version will be displayed.

3. Select the `Easy Setup` package, press `Y`, and enable `Boot Commands` to allow automatic updates in the future.

4. Open `Easy Setup`, choose your preferred installation method, and you're all set!

---

## Supported Hardware

| Model | Chip |
|---|---|
| Nintendo Switch V1 | Erista |
| Nintendo Switch V2 | Mariko |
| Nintendo Switch Lite | Mariko |
| Nintendo Switch OLED | Mariko |

---

## Philosophy

The guiding principle of console overclocking is the absence of side effects. The console should run without Atmosphere errors, game crashes, or thermal shutdowns. Achieving this results in a stable system, improved in-game performance, and balanced power consumption.

---

## Guides

| Guide | Link |
|---|---|
| Overclocking Setup (60 FPS) | https://rentry.co/howtoget60fps |
| Mariko Settings | https://rentry.co/mariko |
| Erista Settings | https://rentry.co/erista |
| Stability Testing | https://rentry.co/howtoteststability |

---

## FAQ

- **Problems after installation?** Try fixing attributes: `Hekate` → `Tools` → `Arch Bit`.
- **Need help?** Reach out on [Horizon OC](https://dsc.gg/horizonoc) or [NSwitch 60FPS Cheats & Mods](https://discord.com/invite/UqN6FcepTQ) (`#overclocking`).

---

## Included Components

- [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
- [Hekate](https://github.com/CTCaer/hekate)
- [Sys-patch](https://github.com/borntohonk/sys-patch)
- [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)
- [Easy Setup](https://github.com/dominatorul/Easy-Setup)

---

## Credits

| Contributor | Role |
|---|---|
| **Lightos's Cat** | Cat |
| **Souldbminer** | hoc-clk and loader development |
| **Lightos** | Loader patches, hoc-clk development, guides |
| **TDRR** | HOC logo design |
| **tetetete-ctrl** | Website design |
| **SciresM** | Atmosphere CFW |
| **CTCaer** | L4T, Hekate, proper RAM timings |
| **KazushiMe** | Switch OC Suite |
| **Hanai3bi (Meha)** | Switch OC Suite, EOS, sys-clk-eos |
| **NaGaa95** | L4T-OC kernel, Status Monitor fork |
| **B3711 (halop)** | EOS, contributions |
| **sys-clk team** (m4xw, p-sam, natinusala) | sys-clk |
| **Dominatorul** | Soctherm driver, guides, general help |
| **ppkantorski** | Ultrahand sys-clk & Status Monitor fork |
| **MasaGratoR** | Status Monitor & Display Refresh Rate driver |
| **MasaGratoR, ZachyCatGames** | General help |
| **Dominatorul, Samybigio, Arcdelta, Miki, Happy, Winnerboi77, Blaise, Alvise, agjeococh, frost, letum00, Xenshen** | Testing |
| **Samybigio2011, Miki** | Italian translations |
| **angelblaster** | Korean translations |
| **q1332348216-glitch** | Chinese translations |
| **Nvidia** | [Tegra X1 TRM](https://developer.nvidia.com/embedded/dlc/tegra-x1-technical-reference-manual), soctherm driver, L4T |

---

*Made with love by Dominatorul* ❤️
