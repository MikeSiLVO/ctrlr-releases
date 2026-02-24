# Changelog

## [1.0.0] - 2026-02-24

Initial public release.

### Fixed
- App icon blurry on Windows (`.ico` was missing higher-resolution layers)
- Release artifacts now have platform-friendly filenames

### Added
- Full torrent management: add (magnet/file/URL), pause, resume, remove, recheck, reannounce
- Detail panel with General, Files (folder tree), Peers, Trackers, and Speed Graph tabs
- Multi-add dialog with per-torrent options, file selection, and extra trackers
- Connection types: SSH tunnel, TCP/SCGI, HTTP JSON-RPC, XML-RPC over HTTPS
- Multi-instance profiles with quick-switch from toolbar
- RSS feeds with regex rules, smart episode tracking, quality preferences, auto-download
- Bandwidth scheduler with 7x24 grid and named speed profiles
- Torrent history with .torrent blob archive, search, and re-add/export
- Named throttle groups, ratio groups with auto-actions, tag management
- Drag-drop, keyboard shortcuts, deep links, .torrent file associations
- System tray with start minimized and close-to-tray
- Autostart on system boot
- 5 themes: Dark, Light, Midnight, Nord, Dracula
- 7 languages: English, German, Spanish, French, Portuguese (BR), Russian, Chinese
- Activity log persisted to SQLite
- Remote settings management with capability detection
- Disk space monitoring with seedbox provider support
- Cross-platform: Windows (NSIS), macOS (DMG), Linux (DEB/AppImage)
