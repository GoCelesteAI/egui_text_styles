# Text Styles

**Episode 16** of the [Learn egui in Neovim](https://www.youtube.com/playlist?list=PLmVt_7TEzoxiUTNj3Fq9XdYyCKuBMSn7E) series.

Style text with colors and formatting using `RichText`, `Color32`, and egui's text styling API.

## Features

- `RichText::new()` with `.strong()`, `.italics()`, `.strikethrough()`, `.underline()`, `.monospace()`
- `Color32::from_rgb()` for custom text colors
- `.size()` for font size control
- `ctx.set_pixels_per_point()` for UI scaling
- Toggleable sections with checkboxes
- Font size slider (12–40)

## Run

```sh
cargo run
```

## Series

Learn egui in Neovim — build desktop GUI apps with Rust and egui, edited entirely in Neovim.
