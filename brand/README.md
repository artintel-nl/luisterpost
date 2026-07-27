# Luisterpost — identity assets

Mark: **The Post** (direction 1a). A mast on a ground line with a signal cap and one
intake arc on each side — a WW2 field listening post, reduced to five strokes.

## Files

| File | Use |
|---|---|
| `mark-on-dark.svg` | primary mark, dark backgrounds |
| `mark-on-light.svg` | primary mark, paper/light backgrounds |
| `mark-black.svg` | one-colour, black (print, stamps, embroidery) |
| `mark-white.svg` | one-colour, white (knock-out) |
| `lockup-on-dark.svg` | horizontal lockup, dark |
| `lockup-on-light.svg` | horizontal lockup, light |
| `favicon.svg` | 16–64px, ships its own dark tile so it survives both browser themes |
| `app-icon-512.svg` | GitHub org/repo avatar, PWA icon, sticker |

## Palette

| Token | Hex | Role |
|---|---|---|
| Ink (dark) | `#1a1c17` | strokes on light |
| Ink (light) | `#ece8dd` | strokes on dark |
| Signal | `#d9963f` | intake arcs, live indicators |
| Tile | `#171a14` | dashboard ground |
| Paper | `#f4f1e8` | light ground |

## Type

Archivo 700, uppercase, `letter-spacing: 0.2em` for the wordmark.
JetBrains Mono 400/700, uppercase, `0.14em` for labels, station names, and status text.
The lockup SVGs reference Archivo by name — **convert the text to outlines** before
using them anywhere the font is not loaded.

## Rules

- Clear space: half the mark's height on all four sides.
- Minimum sizes: mark 16px, lockup 120px wide.
- The signal arcs are the only place the accent appears in the mark. Do not recolour the mast.
- Below 20px use the mark alone, never the lockup.
- The arcs may animate (fade in outward, ~1.2s loop) to indicate a live receiver. The mast never moves.
