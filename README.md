# Material Solarized Dark

[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/albex.material-solarized-dark?style=flat-square&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=albex.material-solarized-dark)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/albex.material-solarized-dark?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=albex.material-solarized-dark)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/Albex/material-solarized-dark?style=flat-square&logo=github)](https://github.com/Albex/material-solarized-dark/releases)
[![CI](https://github.com/Albex/material-solarized-dark/actions/workflows/release.yml/badge.svg)](https://github.com/Albex/material-solarized-dark/actions/workflows/release.yml)

Solarized Dark color theme for **VS Code**, inspired by the Solarized Dark theme from Material Lite IntelliJ plugin.

## Preview

A beautiful dark theme combining the best of **Solarized Dark** color palette with **Material Theme** UI aesthetics.

## Installation

### From VS Code Marketplace
1. Open VS Code
2. Go to Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for `Material Solarized Dark`
4. Click Install

### From VSIX
1. Download the latest `.vsix` from [Releases](https://github.com/Albex/material-solarized-dark/releases)
2. In VS Code, go to Extensions view
3. Click the `...` menu and select `Install from VSIX...`
4. Select the downloaded `.vsix` file

## Usage

After installation:
1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Run `Preferences: Color Theme`
3. Select `Material Solarized Dark`

## Development

### Prerequisites
- Node.js (v16 or later)
- npm or yarn

### Package the extension
```bash
# Install vsce globally
npm install -g @vscode/vsce

# Package the extension
npm run package

# Or generate the vsix file directly
npm run package:vsix
```

### Release

To create a new release:
1. Update the version in `package.json`
2. Create and push a new tag:
   ```bash
   git tag v0.1.2
   git push origin v0.1.2
   ```
3. The GitHub Actions workflow will automatically build and publish the release

## License

[GPL v3](LICENSE) - Feel free to use, modify, and distribute.

---

**Enjoy coding with Material Solarized Dark!** 🎨💻
