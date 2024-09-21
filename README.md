# Mateusz Pietrzak's Personal Configuration

In this repo I store everything needed to get my NixOS configuration up and running.

I store this repository in my home directory.

This setup also relies on home-manager, which has to be installed [separately](https://nix-community.github.io/home-manager/index.xhtml#ch-installation), and [Berkeley Mono](https://berkeleygraphics.com/typefaces/berkeley-mono/), which I obviously cannot provide here.

## Applying Configuration

```
cd ~/.dotfiles
sudo nixos-rebuild switch --flake .
home-manager switch --flake .
```

## What's inside

- KDE Plasma
- Nvidia setup in sync mode
- Pipewire for sound
- Alacritty with my personal configuration
- VSCodium with plugins and configuration
- My name and email for Git