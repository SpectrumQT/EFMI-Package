<h1 align="center">Endfield Model Importer</h1>

<h4 align="center">Custom 3d models loader for Arknights: Endfield</h4>

<p align="center">
  <a href="#disclaimers">Disclaimers</a> •
  <a href="#features">Features</a> •
  <a href="#efmi-installation">EFMI Installation</a> •
  <a href="#known-issues">Known Issues</a> •
  <a href="#mod-installation">Mod Installation</a> • 
  <a href="#mod-hot-load">Mod Hot Load</a> • 
  <a href="#mod-user-hotkeys">Mod User Hotkeys</a> • 
  <a href="#mod-development">Mod Development</a> • 
  <a href="#mod-developer-hotkeys">Mod Developer Hotkeys</a> • 
  <a href="#resources">Resources</a> •
  <a href="#license">License</a>
</p>

## Disclaimers  

- **WARNING** — If some **pre-EFMI** mods are not loading, it means that they are **not compatible**. **EFMI** is built with **performance** in mind, so it won't mindlessly calculate 50000 unneeded hashes per frame. Let 5-years old GIMI approach rest in piece, it's not applicable to modern games without huge performance impact (of up to 50% FPS).

## Features

- **Plug-and-Play** — Fully automated installation and game configuration via **[XXMI Launcher](https://github.com/SpectrumQT/XXMI-Launcher)**
- **Highly Optimized** — Built with minimization of performance footprint in mind
- **Modder Friendly** — Enables fully automatic model re-import mod creation with **[EFMI Tools](https://github.com/SpectrumQT/EFMI-Tools)**

## Planned Features

- **Bone Merging** — Dynamic skeleton data merging to allow modders work with unified VG list
- **Static Objects Support** — In-game static objects replacement (technically it's toolkit-side feature)

## EFMI Installation

1. Download the [latest release](https://github.com/SpectrumQT/XXMI-Launcher/releases/latest) of **XXMI-Launcher-Installer-Online-vX.X.X.msi**
2. Run **XXMI-Launcher-Installer-Online-vX.X.X.msi** with Double-Click.
3. Click **[Quick Installation]** to install **XXMI Launcher** to the default location (`%AppData%\XXMI Launcher`) or use **[Custom Installation]** to set another folder.
4. On game selection page of **XXMI Launcher** window click Wuthering Waves tile to add EFMI icon to the top-left corner.
5. Click EFMI icon to open EFMI launcher page and press **[Install]** button to download and install EFMI.

## Mod Installation

1. [Extract](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-f6dde0a7-0fec-8294-e1d3-703ed85e7ebc) mod's archive
2. Put extracted folder into the **Mods** folder

## Mod Hot Load

To properly load newly installed mod without restarting the game:
1. Install mod
2. Hide modded character from screen (switch to another)
3. Press **[F10]** to reload EFMI

## Mod User Hotkeys

- **[F10]**: Reload EFMI and Save Mod Settings
- **[F11]**: Toggle EFMI-based mods
- **[F12]**: Toggle User Guide
- **[Ctrl]+[Alt]+[F10]**: Reset Mod Settings and Reload

## Mod Development
To get into mod creation refer to the **EFMI Tools** and its [Modder Guide](https://github.com/SpectrumQT/EFMI-Tools/blob/main/guides/modder_guide.md):
Links: [GitHub](https://github.com/SpectrumQT/EFMI-Tools) ([Mirror: Gamebanana](https://gamebanana.com/tools/21847))

## Mod Developer Hotkeys

- **[Ctrl]+[F10]**: Toggle Perfomance Monitor
- **[Ctrl]+[F11]**: Disable custom shaders while held
- **[Ctrl]+[F12]**: Toggle Hunting Mode Guide
- **Numpad [0]**: Toggle Hunting Mode (green text, make sure to **Enable Hunting** in **XXMI Launcher > Settings > EFMI** )

## Resources

- [EFMI GitHub (you're here)] ([Mirror: Gamebanana](https://gamebanana.com/tools/21846))
- [XXMI Launcher GitHub](https://github.com/SpectrumQT/XXMI-Launcher)
- [EFMI Tools GitHub](https://github.com/SpectrumQT/EFMI-Tools) ([Mirror: Gamebanana](https://gamebanana.com/tools/21847))
- [EFMI Assets](https://github.com/SpectrumQT/EFMI-Assets)
- [Arknights: Endfield Mods - Gamebanana](https://gamebanana.com/games/21842)
- [Discord Modding Community](https://discord.com/invite/agmg)

## Credits

- Chiri, [Bo3b](https://github.com/bo3b), [DarkStarSword](https://github.com/DarkStarSword) - creators of original 3dmigoto, huge thanks to those guys!
- [SilentNightSound](https://github.com/SilentNightSound) - 3dmigoto modding pioneering, AGMG legend (ary Sucrose enjoyer)
- [SpectrumQT](https://github.com/SpectrumQT) - EFMI Development
- [SinsOfSeven](https://github.com/SinsOfSeven), [Gustav0](https://github.com/Seris0), [LeoTorrez](https://github.com/leotorrez) - EFMI Contribution

## License

EFMI is licensed under the [GPLv3 License](https://github.com/SpectrumQT/EFMI/blob/main/LICENSE).
