# Lantide Data — Installers

Public release channel for **full desktop installers** of [Lantide Data](https://github.com/chris19961/lantide-data).

This repository contains **installers only** — no application source code.

## Download

Go to **[Releases](https://github.com/chris19961/lantide-data-installer/releases)** and download the latest installer for your platform:

| Platform | Asset |
| -------- | ----- |
| Windows  | `.exe` (NSIS installer) |
| macOS    | `.dmg` |

Install the package, then launch **Lantide Data** from the Start menu or Applications folder.

## Updates after install

- **Most updates** — In the app: **Help → Check for Updates…** (hot update; no reinstall needed).
- **Full reinstall required** — If the app shows **Full installer required**, download the latest installer from this page and install again.

Hot-update assets (`update-win.zip`, `update-mac.zip`, `version_meta.json`) are published in a separate repository:  
[lantide-data-releases](https://github.com/chris19961/lantide-data-releases)

## For maintainers

| Channel | Repository | Contents |
| ------- | ---------- | -------- |
| Hot updates | [lantide-data-releases](https://github.com/chris19961/lantide-data-releases) | `version_meta.json`, platform zips |
| **Installers (this repo)** | **lantide-data-installer** | NSIS / DMG per release |

Do **not** commit build artifacts to git — use GitHub Releases only.

## License

Same as the main Lantide Data product. See the primary repository for license terms.
