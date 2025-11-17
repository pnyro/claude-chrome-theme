# Claude Chrome Theme

A warm, earthy dark theme for Chrome inspired by [Claude's VSCode theme](https://github.com/pnyro/claude-vscode-theme), featuring rich terracotta accents and sophisticated brown tones.

## Features

- 🎨 **Cohesive Color Palette**: Based on the official Claude VSCode theme colors
- 🌙 **Dark Mode**: Easy on the eyes with warm, rich tones
- 🔥 **Terracotta Accents**: Distinctive #C15F3C (Crail) accent color throughout
- 🎯 **Complete Coverage**: All browser UI elements themed including tabs, toolbar, bookmarks, and New Tab Page

## Color Scheme

The theme uses the following primary colors from the Claude VSCode theme:

| Element | Color | Hex | RGB |
|---------|-------|-----|-----|
| Frame & Backgrounds | Very Dark Warm Brown | `#16140f` | `[22, 20, 15]` |
| Toolbar | Dark Warm Brown | `#1a1816` | `[26, 24, 22]` |
| Active Tab Text & Accents | Crail (Terracotta) | `#C15F3C` | `[193, 95, 60]` |
| Text & Bookmarks | Warm Off-White | `#e8e6e3` | `[232, 230, 227]` |
| Inactive Tab Text | Muted Warm Gray | `#6e6960` | `[110, 105, 96]` |
| Buttons | Secondary Background | `#2d2820` | `[45, 40, 32]` |

## Installation

### Method 1: Load Unpacked (For Development/Testing)

1. Clone this repository:
   ```bash
   git clone https://github.com/pnyro/claude-chrome-theme.git
   ```

2. Open Chrome and navigate to `chrome://extensions/`

3. Enable "Developer mode" using the toggle in the top-right corner

4. Click "Load unpacked" and select the `claude-chrome-theme` directory

5. The theme should now be active!

### Method 2: Chrome Web Store (Coming Soon)

The theme will be published to the Chrome Web Store for easier installation.

## Development

### Project Structure

```
claude-chrome-theme/
├── manifest.json       # Theme configuration and color definitions
├── icons/              # Theme icons (16x16, 48x48, 128x128)
├── LICENSE             # MIT License
└── README.md           # This file
```

### Customizing Colors

To customize the theme colors, edit the `colors` object in `manifest.json`. All colors are specified as RGB arrays:

```json
{
  "theme": {
    "colors": {
      "toolbar": [26, 24, 22],
      "tab_text": [193, 95, 60]
      // ... more colors
    }
  }
}
```

For a complete list of available color properties, see the [Chrome Theme Documentation](https://developer.chrome.com/docs/extensions/develop/ui/themes).

## Browser Compatibility

- ✅ Google Chrome (Manifest V3)
- ✅ Microsoft Edge
- ✅ Brave Browser
- ✅ Other Chromium-based browsers

## Related Projects

- [Claude VSCode Theme](https://github.com/pnyro/claude-vscode-theme) - The original VSCode theme this is based on

## License

MIT License - see [LICENSE](LICENSE) file for details

## Credits

Created by adapting the color scheme from the [Claude VSCode Dark Theme](https://github.com/pnyro/claude-vscode-theme/blob/master/themes/claude-dark.json).
