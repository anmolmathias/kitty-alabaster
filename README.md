# Alabaster theme for [kitty](https://sw.kovidgoyal.net/kitty/)

A light/dark color scheme for the kitty terminal


![Colortest](./assets/colorsTest.png)


![Colortest](./assets/colorsTestDark.png)

Based on the [Alabaster Sublime Scheme](https://github.com/tonsky/sublime-scheme-alabaster) by Nikita Prokopov


## Installation

### Manual
Copy the contents of [`alabaster.conf`](https://github.com/anmolmathias/kitty-alabaster/blob/master/alabaster.conf) or [`alabaster-dark.conf`](https://github.com/anmolmathias/kitty-alabaster/blob/master/alabaster-dark.conf) into your kitty config file (usually stored at `~/.config/kitty/kitty.conf`)

### Via `include` directive
Download the theme and place it alongside your config file:
```
$ curl -o ~/.config/kitty/alabaster.conf https://raw.githubusercontent.com/anmolmathias/kitty-alabaster/master/alabaster.conf
```
Import it by adding `include ./alabaster.conf` at the bottom of your config file.
Substitute with `alabaster-dark.conf` in the above commands for the dark version.

### Via `kitten`
Alternatively download the theme file into your kitty theme directory (usually `~/.config/kitty/themes`) and then use the themes kitten to select 'Alabaster'. `kitty +kitten themes --reload-in=all Alabaster`
Substitute with `Alabaster Dark` in the above commands for the dark version.

## License

[MIT License](./LICENSE)