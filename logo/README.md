# Logo

The RSVIM logo is generated from assets:

- [rust-logo-blk.svg](https://github.com/rust-lang/rust-artwork/blob/master/logo/rust-logo-blk.svg) downloaded from [Rust artwork](https://github.com/rust-lang/rust-artwork) (see [Rust logo](https://en.wikipedia.org/wiki/File:Rust_programming_language_black_logo.svg)) .
- [rustacean-flat-noshadow.svg](https://rustacean.net/assets/rustacean-flat-noshadow.svg).
- [Google font - Alfa Slab One](https://fonts.google.com/specimen/Alfa+Slab+One?preview.text=Rsvim&categoryFilters=Serif:%2FSerif%2FFat+Face) and exported from [Google Font to Svg Path](https://danmarshall.github.io/google-font-to-svg-path/) with:
  - Letter `R`: size 70, RGB `#000`
  - Letter `S`: size 40, RGB `#F74C00`
  - Letter `VIM`: size 40, RGB `#000`

With SVG editing tools:

- [figma](https://www.figma.com/design) for editing SVG images.
- [Imagemagick](https://imagemagick.org/) and [Inkscape](https://inkscape.org/) for converting SVG to PNG images.

Convert SVG to PNG images:

> Note: Below commands are running on a mac M1 chip.

- Convert the rectangle `RSVIM-logo.svg` to `RSVIM-logo.png` with: `magick -density 960 RSVIM-logo.svg RSVIM-logo.png`
- Convert the rectangle `RSVIM-logo-square.svg` to `RSVIM-logo-square.png` with: `magick -density 960 RSVIM-logo-square.svg RSVIM-logo-square.png`
