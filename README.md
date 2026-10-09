# Athanor Vellum

An [Omarchy](https://omarchy.org) theme based on
[**Athanor**](https://github.com/script-wizards/athanor) by Script Wizards, an
alchemical layer for Arch and Hyprland.

Iron-gall ink on parchment. A light theme built from Athanor's **Vellum** palette. In Athanor
the four color schemes are stages of the Magnum Opus, and Vellum is
*albedo*, the whitening.

![Athanor Vellum](preview.png)

## Install

```sh
omarchy theme install https://github.com/nacapulque/omarchy-athanor-vellum-theme
```

Cycle through the eight Doré plates and the logo wallpaper with `omarchy theme bg next`.

Companion theme: [Athanor Umber](https://github.com/nacapulque/omarchy-athanor-umber-theme).

## What's in it

- `colors.toml`: Athanor's Vellum palette and its 16 ANSI colors, mapped onto
  Omarchy's color names. Omarchy builds the terminal, Hyprland, Neovim, btop,
  VS Code and other configs from it.
- `shell.bar.toml`: the status bar in Athanor's own bar colors.
- `backgrounds/`: Gustave Doré's wood engravings, dithered to two tones with
  Floyd-Steinberg in the palette's ground and ink colors. They're 3840×2160,
  drawn on a 960×540 grid and pixel quadrupled, so the dither stays crisp on 4K
  and scales down cleanly to 1080p. There's also the usual Omarchy logo
  wallpaper in the palette's accent.

Body text has at least 12:1 contrast against the background, and every accent
and ANSI color has at least 4.5:1, so the original's contrast targets hold.

## What's not in it

This is only Athanor's look. The roguelike status line, planetary hours, tarot
draws, lockscreen sigils, a plate per workspace, the bitmap fonts and the notch
plugin all belong to [Athanor itself](https://github.com/script-wizards/athanor),
so install it if you want the whole furnace.

## Credits

- Palette, dither recipe and the idea: [Athanor](https://github.com/script-wizards/athanor),
  MIT, © 2026 Script Wizards. This theme isn't affiliated with or endorsed by them.
- Plates by Gustave Doré, public domain, from Wikimedia Commons:
- *Merlin leads the king out of the ruins* (Idylls of the King, 1868): <https://commons.wikimedia.org/wiki/File:Idylls_of_the_King_1.jpg>
- *Merlin shows the book* (Idylls of the King, 1868): <https://commons.wikimedia.org/wiki/File:Idylls_of_the_King_15.jpg>
- *Merlin and Vivien under the oak* (Idylls of the King, 1868): <https://commons.wikimedia.org/wiki/File:Idylls_of_the_King_10.jpg>
- *The old man in the grotto* (Idylls of the King, 1868): <https://commons.wikimedia.org/wiki/File:Idylls_of_the_King_17.jpg>
- *Hooded figures in the black forest* (Orlando Furioso, 1879): <https://commons.wikimedia.org/wiki/File:Orlando_Furioso_31.jpg>
- *The lamp-lit hall* (Orlando Furioso, 1879): <https://commons.wikimedia.org/wiki/File:Orlando_Furioso_6.jpg>
- *The graveyard under the moon* (The Raven, 1884): <https://commons.wikimedia.org/wiki/File:Dore_The_Raven_1884-15.jpg>
- *Satan's despair* (Paradise Lost, 1866): <https://commons.wikimedia.org/wiki/File:Gustave_Dore_Satan%27s_Despair.jpg>
