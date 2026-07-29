# 🎨 Linux Dotfiles — Multi-Theme Rice Setup

This repository contains dotfile configurations for Linux (KDE Plasma 6, Fedora), split into two distinct theme variations:

1. **`dark-monochrome/`** (Default): A minimalist e-reader inspired theme with a dark charcoal background (`#1e1d1c`), crisp light text (`#d4d2cf`), and subtle matte gray accents. No bright color hues.
2. **`mocha/`**: The vibrant Catppuccin Mocha (Blue accent) theme setup.

---

## 🛠️ Applications Covered

- **Ghostty**: Terminal configuration, shaders (`cursor_warp.glsl`, `ripple_cursor.glsl`), and color palettes
- **KDE Plasma & KWin**: Global color schemes (`DarkMonochrome` / `CatppuccinMochaBlue`), Aurorae window decorations (`DarkMonochrome-Modern` / `CatppuccinMocha-Modern`), Dolphin file manager, and Elisa configs
- **Zen Browser**: Custom `userChrome.css` and `userContent.css` covering UI and internal `about:` pages
- **Starship**: Segmented prompt configurations (`mono` and `catppuccin_mocha` palettes)
- **btop**: Custom system monitor themes (`mono.theme` and `mocha.theme`)
- **Fastfetch**: Scaled terminal system information layout and colors
- **GTK 3 & 4**: Auto-matched GTK color schemes and assets

---

## 🚀 Usage

### Restore Dark Monochrome Rice (Default)
```bash
./restore.sh dark-monochrome
```

### Restore Catppuccin Mocha Rice
```bash
./restore.sh mocha
```

---

## 📁 Repository Structure

```
dotfiles/
├── README.md
├── restore.sh
├── dark-monochrome/
│   ├── btop/
│   ├── cava/
│   ├── fastfetch/
│   ├── fish/
│   ├── ghostty/
│   ├── gtk-3.0/
│   ├── gtk-4.0/
│   ├── kde/
│   ├── starship/
│   └── zen-browser/
└── mocha/
    ├── btop/
    ├── cava/
    ├── fastfetch/
    ├── fish/
    ├── ghostty/
    ├── gtk-3.0/
    ├── gtk-4.0/
    ├── kde/
    ├── starship/
    └── zen-browser/
```
