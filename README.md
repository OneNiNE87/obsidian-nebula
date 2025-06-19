# Nebula Theme for Obsidian

A modern, clean theme for Obsidian with a beautiful nebula-inspired aesthetic. This fork includes performance improvements and modern CSS practices while maintaining the original design philosophy. Over 20,000 downloads and growing!

## Installation

### Method 1: Through Obsidian (Recommended)
1. Open Obsidian Settings
2. Navigate to `Appearance` → `Themes`
3. Click `Manage` and search for "Nebula"
4. Click `Install` and then `Use`

### Method 2: Manual Installation
1. Download the latest release from [GitHub Releases](https://github.com/OneNiNE87/obsidian-nebula/releases)
2. Extract `obsidian.css` and `theme.css` to your vault's `.obsidian/themes/Nebula` folder
3. Select "Nebula" in Obsidian's appearance settings

## Customization

### CSS Variables
You can customize the theme by adding these CSS snippets to your vault's `.obsidian/snippets` folder:

```css
:root {
  --background-primary: #1e1e1e;      /* Main editor background */
  --text-normal: #dcddde;             /* Main text color */
  --text-muted: #999;                 /* Subdued text */
  --text-accent: #7c71dd;             /* Accent color */
  --interactive-accent: #7c71dd;       /* Interactive elements */
}
```

### Sidebar Width
To adjust the minimized sidebar width, add:
```css
.side-dock-ribbon {
  width: 24px;  /* Adjust this value */
}
```

## Features

- Minimalist sidebar design that prioritizes keyboard shortcuts and command palette usage
- System font stack for improved performance
- Beautiful nebula-inspired backgrounds for sidebars and main pane
- Clean, modern typography and spacing

## Usage Notes

The theme intentionally minimizes the leftmost vertical bar (containing multiple tools) as it emphasizes keyboard shortcuts and command palette usage. If you prefer a more prominent sidebar, you can:
- Override styles using CSS snippets (modify classes with `side-dock-ribbon` prefix)
- Choose an alternative theme that better suits your workflow

## Screenshots

![Main View](showcase1.jpg)

![Dark Mode](showcase2.jpg)

![Note Taking](showcase3.jpg)

## Credits

- Original theme by [dlccyes](https://github.com/dlccyes)
- Performance improvements and modernization by [OneNiNE87](https://github.com/OneNiNE87) and GitHub Copilot
- Based on pull request contributions to the original [Obsidian Nebula Theme](https://github.com/dlccyes/obsidian-nebula)

## Changes from Original

- Removed Google Fonts dependency in favor of system fonts
- Improved CSS selector formatting for better maintainability
- Added nebula-themed backgrounds for enhanced visual appeal
- Modernized CSS practices while preserving the original design

## License

MIT License - See LICENSE file for details
