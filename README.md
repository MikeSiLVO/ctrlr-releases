# Ctrl+R

A modern desktop thin client for [rTorrent](https://github.com/rakshasa/rtorrent). Connects to your rTorrent instance over SSH, TCP/SCGI, or HTTP and provides a full-featured GUI for managing torrents.

If you find Ctrl+R useful, [buy me a coffee](https://ko-fi.com/mikesilvo) ☕

![Main view](screenshots/main.png)

![Files tab](screenshots/files.png)

## Download

**[Latest Release](https://github.com/MikeSiLVO/ctrlr-releases/releases/latest)**

| Platform | Installer |
|----------|-----------|
| Windows (x64) | `.exe` (NSIS) |
| macOS (Apple Silicon / Intel via Rosetta) | `.dmg` |
| Linux (x64) | `.deb` / `.AppImage` |

## Installation

### Windows

Run the `.exe` installer. Windows may show a SmartScreen warning since the app is unsigned — click **More info** then **Run anyway**.

### macOS

Open the `.dmg` and drag Ctrl+R to Applications. On first launch, right-click the app and select **Open** to bypass Gatekeeper (required for unsigned apps).

### Linux

**Debian/Ubuntu:**

```sh
sudo dpkg -i ctrl-r_*.deb
```

**AppImage:**

```sh
chmod +x ctrl-r_*.AppImage
./ctrl-r_*.AppImage
```

## System Requirements

- Windows 10+ (x64)
- macOS 10.15+ (Intel or Apple Silicon)
- Linux with WebKitGTK 4.1 (x64)
- A running rTorrent instance to connect to

## License

Copyright (c) 2025 MikeSiLVO. All rights reserved.
