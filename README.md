# Muko-Windows (WIP) (Education Purpose)
- Research on the ideal Windows.
- Link for Discord: https://discord.gg/W496reuwrM

---

Current Workflow
1. Download ISO from https://github.com/gravesoft/msdl
2. Get your unattend.xml from https://github.com/memstechtips/UnattendedWinstall/blob/main/Standard/autounattend.xml
3. Use the Ventoy method to boot it https://github.com/memstechtips/UnattendedWinstall?tab=readme-ov-file#method-3-use-ventoy-auto-install-plugin---video-tutorial
4. Install Windows, during the installation either choose Pro N for Workstations or preferably IoT Enterprise LTSC
5. Activate Windows
6. Run Debloat with https://github.com/Raphire/Win11Debloat
```
& ([scriptblock]::Create((irm "https://win11debloat.raphi.re/")))
```
7. Install winget with https://github.com/asheroto/winget-install
```
irm asheroto.com/winget | iex
```

TODO:
- [ ] Change Windows to EU to enable EEA features
- [ ] Install WSL2 best practice
- [ ] Install Android Emulator
- [ ] List of nice Windows Apps alternative to the current popular ones
- [ ] Backup guide and how to switch to Linux (and the opposite)

---
## App List

| Name | Category        | WinGet                         |
| ------ | ----------------- | -------------------------------- |
| [VSCodium](https://github.com/VSCodium/vscodium)     | IDE             | VSCodium.VSCodium              |
| [Floorp](https://github.com/Floorp-Projects/Floorp)     | Browser, Gecko  | Ablaze.Floorp                  |
| [NanaZip](https://github.com/M2Team/NanaZip)     | File Archiver   | M2Team.NanaZip                 |
| [ShareX](https://github.com/ShareX/ShareX)     | Screenshot      | ShareX.ShareX                  |
| [Flow Launcher](https://github.com/Flow-Launcher/Flow.Launcher)     | Search          | Flow-Launcher.Flow-Launcher    |
| [Godot Engine](https://github.com/godotengine/godot)     | Game Dev        | GodotEngine.GodotEngine        |
| [HandBrake](https://github.com/HandBrake/HandBrake)     | Converter       | HandBrake.HandBrake            |
| [Windows Terminal](https://github.com/Microsoft/Terminal)     | Terminal        | Microsoft.WindowsTerminal      |
| [OBS](https://github.com/obsproject/obs-studio)     | Screen Recorder | OBSProject.OBSStudio           |
| [Playnite](https://github.com/JosefNemec/Playnite)     | Game Library    | Playnite.Playnite              |
| [Bruno](https://github.com/usebruno/bruno)     | API Client      | Bruno.Bruno                    |
| [NVCleanstall](https://www.techpowerup.com/nvcleanstall)     | Driver          | TechPowerUp.NVCleanstall       |
| [BCUninstaller](https://github.com/Klocman/Bulk-Crap-Uninstaller)     | Uninstaller     | Klocman.BulkCrapUninstaller    |
| [VLC](https://github.com/videolan/vlc)     | Media Player    | VideoLAN.VLC                   |
| [KDE Connect](https://invent.kde.org/network/kdeconnect-kde)     | Mobile Connect  | KDE.KDEConnect                 |
| [Espanso](https://github.com/espanso/espanso)     | Autocomplete    | Espanso.Espanso                |
| [Windhawk](https://github.com/ramensoftware/windhawk)     | Tweak           | RamenSoftware.Windhawk         |
| [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher)     | Tweak           | valinet.ExplorerPatcher        |
| [DevToys](https://github.com/veler/DevToys)     | Dev             | DevToys-app.DevToys            |
| [Backrest](https://github.com/garethgeorge/backrest)     | Backup          |                                |
| [File Converter](https://github.com/Tichau/FileConverter)     | Converter       | AdrienAllard.FileConverter     |
| [VMware Workstation Pro](https://www.vmware.com/products/workstation-pro.html)     | VM              |                                |
| [Windows Calculator](https://github.com/Microsoft/calculator)     | Calculator      | 9WZDNCRFHVN5                   |
| [RSS Guard](https://github.com/martinrotter/rssguard)     | RSS             | martinrotter.RSSGuard          |
| [Tor Browser](https://gitlab.torproject.org/tpo/applications/tor-browser)     | Browser         | TorProject.TorBrowser          |
| [Pinegrow](https://pinegrow.com)     | CSS             |                                |
| [Articy](https://articy.com)     | Story           |                                |
| [komorebi](https://github.com/LGUG2Z/komorebi)     | Auto-Tiling     | LGUG2Z.komorebi LGUG2Z.whkd    |
| [Directory Opus](https://www.gpsoft.com.au)     | File Manager    | GPSoftware.DirectoryOpus       |
| [Seelen UI](https://github.com/eythaann/Seelen-UI)     | DE, Auto-Tiling | Seelen.SeelenUI                |
| [LosslessCut](https://github.com/mifi/lossless-cut)     | Video Editing   |                                |
| [Zen Browser](https://github.com/zen-browser/desktop)     | Browser, Gecko  | Zen-Team.Zen-Browser.Optimized |
| [DaVinci Resolve](https://blackmagicdesign.com/products/davinciresolve)     | Video Editing   |                                |
| [SiYuan](https://github.com/siyuan-note/siyuan)     | PKM             | B3log.SiYuan                   |
| [qBittorrent](https://qbittorrent.org)     | Torrent         | qBittorrent.qBittorrent        |
| [JDownloader](https://jdownloader.org)     | Download        | AppWork.JDownloader            |
| [Krita](https://krita.org)     | Image Editing   | KDE.Krita                      |

---
## Disclaimer: Later
