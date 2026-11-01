# BS-VChanger figure

The schematic and social preview for the landing page.

| File | What it is |
|---|---|
| `poster.svg` | Hand-drawn schematic shown on the landing page |
| `poster-phone.svg` | Vertical version shown at 560 px wide or less |
| `poster.png` | `poster.svg` rendered for the `og:image` social preview; re-render it if the schematic changes |

## Accuracy

Values come from `src/profiles/built_in.rs` and the signal path from `src/audio/engine.rs` in
[BS-VChanger-Rust](https://github.com/seanmryan73/BS-VChanger-Rust). The schematic shows the Deep
Voice profile using six of the app's 17 effects. Check it against those files if the profile changes.
