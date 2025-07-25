# pywal-discord

pywal-discord is a tool that makes and applies theme to Discord with colors generated by [pywal](https://github.com/dylanaraps/pywal)

## Requires

- Any CSS loader for Discord (default configuration for BetterDiscord, Vencord and Vesktop)
- pywal and its forks (`pip install --user pywal`)

## Works on

- Linux
- MacOS

## Installation

### Arch Linux

`pywal-discord` is available in the Arch Linux repos as `pywal-discord-git`.

### Manual/Git install

```Bash
cd pywal-discord
sudo ./install
```

![gif](https://raw.githubusercontent.com/NecRaul/pywal-discord/master/images/out.gif)

## Configuration

Add your themes to `$XDG_CONFIG_HOME/pywal-discord-themes/` following the `pywal-discord-<theme_name>.css` format.

You can copy `/usr/share/pywal-discord/pywal-discord-default.css` to use as a template.

To use the themes simply call `pywal-discord -t <theme_name>`.

### Theme made by [about123](https://github.com/abou123)

To use this theme

```Bash
./pywal-discord -t abou
```

![gif](https://j.gifs.com/jZPm0W.gif)
