# Cat

A dark Omarchy theme about cats. The palette is taken straight from the wallpapers: the near-black of the
Siamese's mask, cream fur, ginger tabby orange, calico rust, fern green, yarn teal and the Siamese's blue
eyes. The accent is a cool steel gray with a metallic feel.

## Install

```bash
omarchy theme install https://github.com/psychokk/omarchy-cat-theme
omarchy theme set cat
```

Cycle wallpapers with `omarchy theme bg next`.

## What's inside

- `colors.toml`: palette (drives terminal, Waybar, Walker, Mako, Hyprlock, SwayOSD, btop and more)
- `backgrounds/`: six painted cat wallpapers (2576x1438)
  - `1-siamese.jpg` (main, has an animated intro), `2-calico.jpg`, `3-orange.jpg`, `4-tabby.jpg`, `5-gray.jpg`, `6-black.jpg`
- `backgrounds/intros/1-siamese.mp4`: 7.5 s intro. The Siamese wakes up, looks around, blinks twice and
  settles on the still wallpaper
- `preview.png`

Intros play at boot, on theme switch and when picking the background. Turn them off with
`omarchy theme bg intro disable`. Wallpapers without an intro file are simply shown as stills.

## Palette

| Role | Color |
|---|---|
| background | `#0c0d0f` |
| foreground | `#d9cfc0` |
| accent | `#9fa6af` |
| cursor | `#cfd4da` |
| muted | `#6b6a60` |

## Credits

Wallpaper artwork provided by the theme author. Intro animation generated from the wallpaper itself.

## Notes

The theme follows the documented Omarchy 4 layout but has not been verified on a live install yet.
Please open an issue if something looks off.
