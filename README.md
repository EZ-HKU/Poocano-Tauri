# Poocano with Tauri
A third party Tripleuni client built with Tauri.

## Supported platforms
- [X] Windows (.exe, .msi)
- [X] macOS (.dmg)
- [X] Android (.apk)
- [X] Linux (build from source only)

## Installation
### Download the latest release
You can download the latest release from the [releases page](https://github.com/EZ-HKU/Poocano-Tauri/releases).

### Or build from source
1. Prerequisites
- [Node.js](https://nodejs.org/)
- [Rust](https://www.rust-lang.org/)
- [Tauri CLI](https://tauri.studio/docs/getting-started/setup-installation)

2. clone and build
```bash
git clone https://github.com/EZ-HKU/Poocano-Tauri.git
cd Poocano-Tauri
npm install
npm run tauri build
```