# launcher-updates

Public update feed repository for Conscherry Launcher.

This repository is intentionally separate from the private source code repository.

What gets published here (via GitHub Releases):
- Windows:
	- NSIS installer `.exe`
	- installer `.exe.blockmap`
	- `latest.yml` (Windows update metadata)
- macOS (x64 and arm64):
	- `.dmg` and `.zip` bundles
	- `.dmg.blockmap` and `.zip.blockmap`
	- `latest-mac.yml` (macOS update metadata)
- Linux (x64):
	- `.AppImage`, `.deb`, `.rpm`
	- `latest-linux.yml` (Linux update metadata)

Update notes in this repo:
- Per-version markdown notes are stored in `updates/`
- Index of notes: `updates/README.md`