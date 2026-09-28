# Plank Themes — Linux Mint 22.3 Compatible Collection

A cleaned, verified collection of **72 Plank dock themes** compatible with the current
generation of the Plank dock (**plank-reloaded**) on **Linux Mint 22.3 (Zena)** —
Ubuntu 24.04 Noble base, Cinnamon 6.6.

Forked from [erikdubois/plankthemes](https://github.com/erikdubois/plankthemes)
(117 stars — all credit for the themes goes to Erik Dubois and the original authors).

## What was changed in this fork

| Change | Reason |
|---|---|
| Kept **72 themes** using the modern `[PlankTheme]` format | 100% compatible with plank / plank-reloaded |
| Removed **38 themes** using the legacy 2013 `[PlankDrawingTheme]` format | Not parsed by modern Plank — they would not render |
| Updated this README | Verification notes for Linux Mint 22.3 |

## Compatibility

- ✅ Verified on **Linux Mint 22.3 (Zena)** — Cinnamon 6.6 — plank-reloaded
- ✅ Theme format matches the themes shipped with plank-reloaded (`Default`, `Matte`, `Matte-Light`, …)
- ✅ No scripts, no sudo, no system changes — plain theme folders only

## Installation

```bash
git clone https://github.com/X0Riii/plankthemes.git /tmp/plankthemes
mkdir -p ~/.local/share/plank/themes
cp -r /tmp/plankthemes/* ~/.local/share/plank/themes/
```

Then apply a theme:

- **GUI**: Ctrl + right-click on the dock → Preferences → Appearance → Theme
- **CLI**:
  ```bash
  gsettings set net.launchpad.plank.dock.settings:/net/launchpad/plank/docks/dock1/ theme 'Arc'
  ```

## Theme list (72)

Apollo, Arc, ArchLabs, Arsa, Arsa-Transparent, AyasBlue, AyasGreen, AyasRed,
AyasWhite, AyasYellow, Blumix, Chameleon, Champagne, Coal, Darktheon, Elite,
Fresh, Frost, Gingerbread2, GlassPill, GlassPillBlack, Glasseoso, GlasseosoMod,
Gnosemite, Gracieux, HTC, HUD, Holo, Hud, Jupiter-Redux, Jupiter-Redux-2,
Kit-Kat, LightPanel, Lucc, Lunita, Madterky, Mint-Y-Theme, Moka, Moncho,
MonchoMod, Numix, OSXLion, OSXYosemite, OSXYosemite Red, Omda, Orchis, Panel,
Pantheon, PantheonBlack, PantheonNebbia, PantheonNero, PantheonVetro,
Pantheon_black_total, Pantheon_champagne, Pantheon_champagne_black, Pantiva,
PearOS, Placmank, Rosa, RoundedGlass, RoundedGlass2, Sampan, SampanBlack,
SampanBlue, SampanGlass, SampanGreen, SampanPink, SampanWhite, TransPanel,
Translucent-Panel, Transparent, Transparent4Real, Ubuntu, Unity-like,
Vertex-Plank, Whitesnow, Wingy, WingyBlanco, Wingywhity, Xenlism, Youtube,
Zombie queen, Zorin10-Blue, Zorin10-Green, anti-shade, ceghap, cratos-lion,
cublinux, eLight, froggaz

## License

Themes keep the license of their original authors (see upstream repository).
