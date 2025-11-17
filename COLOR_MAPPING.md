# Color Mapping: VSCode to Chrome Theme

This document shows how colors from the [Claude VSCode Dark Theme](https://github.com/pnyro/claude-vscode-theme/blob/master/themes/claude-dark.json) were mapped to the Chrome theme.

## VSCode Theme Source Colors

### Primary Brand Colors
- **Crail**: `#C15F3C` → RGB `[193, 95, 60]` - Warm terracotta/orange-brown accent
- **Cloudy**: `#B1ADA1` → RGB `[177, 173, 161]` - Warm gray-taupe
- **Pampas**: `#F4F3EE` → RGB `[244, 243, 238]` - Warm off-white/cream

### Editor Interface Colors
- **Editor Background**: `#1a1816` → RGB `[26, 24, 22]`
- **Foreground Text**: `#e8e6e3` → RGB `[232, 230, 227]`
- **Line Numbers**: `#6e6960` → RGB `[110, 105, 96]`
- **Sidebar/Activity Bar**: `#16140f` → RGB `[22, 20, 15]`
- **Secondary Background**: `#2d2820` → RGB `[45, 40, 32]`
- **Border Color**: `#2b2621` → RGB `[43, 38, 33]`

## Chrome Theme Color Mapping

| Chrome Property | Source | VSCode Color | RGB Value |
|----------------|--------|--------------|-----------|
| **Frame & Window** | | | |
| `frame` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `frame_inactive` | Editor Background | `#1a1816` | `[26, 24, 22]` |
| `frame_incognito` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `frame_incognito_inactive` | Editor Background | `#1a1816` | `[26, 24, 22]` |
| **Toolbar** | | | |
| `toolbar` | Editor Background | `#1a1816` | `[26, 24, 22]` |
| `toolbar_button_icon` | Crail Accent | `#C15F3C` | `[193, 95, 60]` |
| **Tabs** | | | |
| `tab_text` | Crail Accent | `#C15F3C` | `[193, 95, 60]` |
| `tab_background_text` | Line Numbers (muted) | `#6e6960` | `[110, 105, 96]` |
| `tab_background_text_inactive` | Line Numbers (muted) | `#6e6960` | `[110, 105, 96]` |
| `tab_background_text_incognito` | Line Numbers (muted) | `#6e6960` | `[110, 105, 96]` |
| `tab_background_text_incognito_inactive` | Line Numbers (muted) | `#6e6960` | `[110, 105, 96]` |
| `background_tab` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `background_tab_inactive` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `background_tab_incognito` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `background_tab_incognito_inactive` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| **Bookmarks** | | | |
| `bookmark_text` | Foreground Text | `#e8e6e3` | `[232, 230, 227]` |
| **Buttons & Controls** | | | |
| `button_background` | Secondary Background | `#2d2820` | `[45, 40, 32]` |
| **New Tab Page** | | | |
| `ntp_background` | Sidebar/Activity Bar Background | `#16140f` | `[22, 20, 15]` |
| `ntp_text` | Foreground Text | `#e8e6e3` | `[232, 230, 227]` |
| `ntp_link` | Crail Accent | `#C15F3C` | `[193, 95, 60]` |
| `ntp_header` | Crail Accent | `#C15F3C` | `[193, 95, 60]` |

## Design Principles

### 1. **Hierarchy**
- **Active elements** (active tabs, links, icons) use the distinctive Crail accent `#C15F3C`
- **Inactive elements** use muted warm grays
- **Text** uses the warm off-white for readability

### 2. **Depth**
- **Darkest** (`#16140f`): Frame, inactive tabs, NTP background - creates depth
- **Mid-tone** (`#1a1816`): Toolbar, inactive frame - main surface
- **Accent** (`#2d2820`): Buttons and interactive elements

### 3. **Consistency**
- All incognito mode colors match regular mode colors for consistency
- Warm color temperature maintained throughout (no pure blacks or cool grays)
- Terracotta accent used consistently for interactive and active states

## Color Psychology

The warm, earthy palette creates:
- **Comfort**: Brown tones are associated with stability and warmth
- **Focus**: Dark backgrounds reduce eye strain
- **Distinctiveness**: The terracotta accent provides clear visual hierarchy
- **Sophistication**: Rich, muted tones create a premium feel

## Accessibility Notes

- **Contrast Ratio**: Text colors (`#e8e6e3`) on dark backgrounds (`#1a1816`) provide sufficient contrast (>7:1)
- **Accent Visibility**: The Crail accent (`#C15F3C`) stands out clearly against dark backgrounds
- **Inactive State**: Muted colors (`#6e6960`) clearly distinguish inactive from active elements
