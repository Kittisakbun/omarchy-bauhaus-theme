# Omarchy Theme: Bauhaus

A Bauhaus-inspired dark theme derived from the included backgrounds (Bauhaus01–05.jpg): warm coral and sand accents over cool slate/teal surfaces. All accent colors have been adjusted to meet WCAG AA contrast across core backgrounds.

## Palette
- Primary Background:   #101318 (deep slate-black)
- Secondary Background: #161B22 (soft charcoal)
- Tertiary Background:  #222733 (lifted cool surface)
- Primary Accent:       #E37B66 (coral, WCAG-lifted)
- Secondary Accent:     #E0A568 (sand)
- Tertiary Accent:      #809D9E (muted teal, WCAG-lifted)
- Text Primary:         #EAEFF5 (near-porcelain)
- Text Secondary:       #C6CED8 (cool mist)
- Text Dim:             #98A0AE (slate gray-blue)
- Success:              #789FA2 (WCAG-lifted)
- Warning:              #E7A46F
- Error:                #CB886D (WCAG-lifted)
- Info:                 #8999AA (WCAG-lifted)
- Selection Background: #2B3040

ANSI palettes are encoded in palette.yml and Alacritty config.

## Editors and Tools
This repository includes app themes/config for:
- Alacritty, Waybar, Hyprland, Hyprlock, Mako, btop, Walker, Neovim, Chromium, and icons.

Helix and Yazi themes are managed in dotfiles.

### Yazi
- Theme file: ~/.dotfiles/config/yazi/themes/bauhaus.toml
- Config link: ~/.config/yazi/theme.toml -> ~/.dotfiles/config/yazi/themes/bauhaus.toml

### Vesktop (System24)
- Theme file: ~/.dotfiles/config/vesktop/themes/system24-omarchy-bauhaus.css
- Symlink: ~/.config/vesktop/themes/System24 - Bauhaus.css -> ~/.dotfiles/.../system24-omarchy-bauhaus.css

## Notes
- Colors were extracted from backgrounds/Bauhaus01–05.jpg and tuned to meet WCAG AA on key UI surfaces.
- If you want this theme focused on a single background image, re-open an issue/PR with the chosen file and I’ll retune the palette accordingly.
