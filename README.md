<h1 align="center">Cat</h1>

<p align="center">
  A dark <a href="https://omarchy.org">Omarchy</a> theme about cats.<br>
  Near-black base, steel-gray accent, and a palette picked straight from six painted cat wallpapers.
</p>

<p align="center">
  <img src="preview.png" alt="Cat theme preview" width="860">
</p>

<p align="center"><sub>Preview is a mockup built from the wallpaper and the palette, not a real screenshot.</sub></p>

## Highlights

- **Cat palette**: every color comes from one of the cats (see the table below)
- **Steel-gray accent** `#9fa6af` with a lighter `#cfd4da` cursor for a cool, metallic feel
- **Six painted wallpapers**, with the Siamese as the main one
- **Animated intro** for the Siamese wallpaper: a warm golden light washes across the face and passes
- Dark by design: background `#0c0d0f`

## Wallpapers

<p align="center">
  <img src="images/wallpapers.jpg" alt="The six cat wallpapers" width="900">
</p>

| File | Cat | Intro |
|---|---|---|
| `1-siamese.jpg` | Siamese, close-up with blue eyes (main) | yes |
| `2-calico.jpg` | Calico on an armchair by the window | no |
| `3-orange.jpg` | Orange tabby playing with teal yarn | no |
| `4-tabby.jpg` | Sleeping tabby on a gray blanket | no |
| `5-gray.jpg` | Gray cat watching the rain | no |
| `6-black.jpg` | Black cat asleep on a lap | no |

All wallpapers are 2576x1438. Cycle through them with `omarchy theme bg next`.

## Animated intro

<p align="center">
  <img src="images/intro.gif" alt="Intro animation of the Siamese wallpaper" width="640">
</p>

`backgrounds/intros/1-siamese.mp4` (7.5 s, 2576x1438, 24 fps, H.264). A warm, golden light washes across
the Siamese's face from left to right and passes, while the camera eases back and settles. The last frame
is the wallpaper itself, so the hand-off from video to still is seamless.

The GIF above is a lower-quality version for this page. Intros play at boot, on theme switch and when
picking the background. To turn them off: `omarchy theme bg intro disable`.

## Palette

<p align="center">
  <img src="images/palette.png" alt="Cat palette" width="900">
</p>

| Role | Color | Where it comes from |
|---|---|---|
| background | `#0c0d0f` | the dark backdrop around the Siamese |
| foreground | `#d9cfc0` | cream fur and knitted blankets |
| accent | `#9fa6af` | the gray cat, pushed toward cool steel |
| cursor | `#cfd4da` | lighter steel highlight |
| muted | `#6b6a60` | shadows on the gray cat's coat |
| color1 / color9 | `#b8603c` / `#d97a55` | calico rust |
| color2 / color10 | `#8a9a6a` / `#a8b887` | the fern and pothos in the calico wallpaper |
| color3 / color11 | `#d19a57` / `#e5bf91` | orange tabby fur |
| color4 / color12 | `#5aa7dc` / `#86c0ec` | the Siamese's blue eyes |
| color5 / color13 | `#c58e92` / `#dba9ac` | paw pads and noses |
| color6 / color14 | `#6fb0b5` / `#8fcbcf` | teal yarn |
| color0 / color8 | `#1a1816` / `#4e4038` | black cat and Siamese seal brown |
| color7 / color15 | `#c0bcb0` / `#e5e1cf` | pale fur |

## Install

```bash
omarchy theme install https://github.com/psychokk/omarchy-cat-theme
omarchy theme set cat
```

## What's inside

```
colors.toml                    # palette (terminal, Waybar, Walker, Mako, Hyprlock, SwayOSD, btop, ...)
backgrounds/
  1-siamese.jpg ... 6-black.jpg
  intros/1-siamese.mp4         # animated intro for the main wallpaper
preview.png
images/                        # pictures used by this README
```

## Make it yours

- **Add a wallpaper**: drop a `.jpg` or `.png` into `backgrounds/`. It shows up in `omarchy theme bg next`.
- **Add an intro**: put an `.mp4` with the same base name in `backgrounds/intros/`
  (for example `backgrounds/4-tabby.jpg` and `backgrounds/intros/4-tabby.mp4`). Wallpapers without
  an intro are simply shown as stills.
- **Change the accent**: edit `accent`, `cursor` and `selection_background` in `colors.toml`.

## Credits

Wallpaper artwork provided by the theme author. The intro animation is generated from the Siamese
wallpaper itself.

## Status

The theme follows the documented Omarchy layout but has not been verified on a live install yet.
If something looks off, please open an issue.
