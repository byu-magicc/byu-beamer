# byu-beamer

This is a beamer template for BYU.
The following logos are available:

- BYU
- MAGICC Lab
- RAD Lab

## How to Install

After cloning the repo, you can set the environment variable `TEXINPUTS` so that your LaTeX compiler knows where to find these files:

```sh
TEXINPUTS=".:$HOME/<clone path>/byu-beamer//:"
```

Notes:

- You can set this without exporting it so that it is active for the current terminal
- You can export this variable in your `~/.zshrc` or `~/.bashrc` so it is always available
- You can also look up how to include custom LaTeX files (there is a whole hierarchy of default search locations)

## How to Use

Look at `example.tex` in this repo for how to use the theme.
