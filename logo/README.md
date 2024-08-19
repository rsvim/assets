# Logo

The RSVIM logo is generated from assets:

- [rust-logo-blk.svg](https://github.com/rust-lang/rust-artwork/blob/master/logo/rust-logo-blk.svg) downloaded from [Rust artwork](https://github.com/rust-lang/rust-artwork) (see [Rust logo](https://en.wikipedia.org/wiki/File:Rust_programming_language_black_logo.svg)) .
- [HVD Comic Serif Pro](https://www.hvdfonts.com/fonts/hvd-comic-serif) font exported from [Lucidchart](https://lucid.app/).

With SVG editing tools:

- [svgedit](https://github.com/SVG-Edit/svgedit) for editing SVG images.
- [rsvg-convert](https://gitlab.gnome.org/GNOME/librsvg) command for converting SVG into PNG (see [librsvg](https://en.wikipedia.org/wiki/Librsvg)).

## Generate Logo Pictures

> Note: Below commands are running on a mac OS M1 machine.

1. Create a SVG image that contains upper case characters **"SVIM"** written in "HVD Comic Serif Pro" with Lucidchart.
2. Merge the **"SVIM"** characters SVG with the **"R"** rust logo SVG (see [rust-logo-blk.svg](https://github.com/rsvim/assets/blob/96a7b738e05650d8f360f1d3e8b37f2ca2b2b8d0/logo/detail/rust-logo-blk.svg)), and create the "R-SVIM" SVG image (see [RSVIM-logo.svg](https://github.com/rsvim/assets/blob/96a7b738e05650d8f360f1d3e8b37f2ca2b2b8d0/logo/RSVIM-logo.svg)).
3. Convert the `RSVIM-logo.svg` into PNG with command:

   > `rsvg-convert RSVIM-logo.svg -z 20 -o RSVIM-logo.png`

4. Convert the `RSVIM-logo.svg` into a square-sized PNG with command:

   > `rsvg-convert RSVIM-logo.svg -z 20 --page-width 5860 --page-height 5860 --top 1180 --left 150 -o RSVIM-logo-square.png`

5. Convert the `RSVIM-logo.svg` into a square-sized white-background PNG with command:

   > `rsvg-convert RSVIM-logo.svg -z 20 --page-width 5860 --page-height 5860 --top 1180 --left 150 --background-color white -o RSVIM-logo-square-whitebg.png`

## The Orange Crab Logo

- [rustacean-flat-noshadow.svg](https://rustacean.net/assets/rustacean-flat-noshadow.svg).
