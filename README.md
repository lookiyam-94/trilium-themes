# Omarchy themes for Trilium

[Omarchy](https://omarchy.org) colour themes ported to [Trilium Notes](https://github.com/TriliumNext/Trilium).
Each theme is built on top of TriliumNext's modern `next-dark` UI. It changes colours only and sets no fonts,
so the fonts you pick in **Options → Appearance** still apply.

| Theme | File |
| --- | --- |
| Black Sand | [`themes/black-sand.css`](themes/black-sand.css) |
| Catppuccin | [`themes/catppuccin.css`](themes/catppuccin.css) |
| Ethereal | [`themes/ethereal.css`](themes/ethereal.css) |
| Everforest | [`themes/everforest.css`](themes/everforest.css) |
| Gruvbox | [`themes/gruvbox.css`](themes/gruvbox.css) |
| Hackerman | [`themes/hackerman.css`](themes/hackerman.css) |
| Kanagawa | [`themes/kanagawa.css`](themes/kanagawa.css) |
| Lumon | [`themes/lumon.css`](themes/lumon.css) |
| Miasma | [`themes/miasma.css`](themes/miasma.css) |
| Nord | [`themes/nord.css`](themes/nord.css) |
| Nothing | [`themes/nothing.css`](themes/nothing.css) |
| Tokyo Night | [`themes/tokyo-night.css`](themes/tokyo-night.css) |

The Nothing theme follows [omarchy-nothing-theme](https://github.com/lookiyam-94/omarchy-nothing-theme):
monochrome greys, with red used only for "where you are" (the active note, the active tab, the focused input and the cursor).

## Install

1. In Trilium, create a new note of type **Code** and set its language to **CSS**.
2. Paste in the contents of the theme file.
3. Add these labels to the note (use any unique name for the theme):
   ```
   #appTheme=omarchy-nothing #appThemeBase=next-dark
   ```
   `appThemeBase=next-dark` loads TriliumNext's modern UI under the theme. Without it, the theme sits on top of the legacy layout.
   Every theme needs its own `appTheme` value, otherwise only one of them shows up in the list.
4. Go to **Menu → Options → Appearance → Theme**, pick the theme, and press `Ctrl+R` to reload.

Tested on TriliumNext 0.105/0.106.

## License

MIT
