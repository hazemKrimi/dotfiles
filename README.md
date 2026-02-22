# Dotfiles

This repo contains the dotfiles of essential programs configurations I use across my Linux devices.

## Requirements

You need to have [Git](https://git-scm.com/downloads) and [GNU stow](http://gnu.org/software/stow/) to link the dotfiles properly. You also need to install a [Nerd Font](https://www.nerdfonts.com). If you don't want a nerd font you can disable it from `alacritty.toml`.

## Installation

1. Clone the repo

```
git clone https://github.com/hazemKrimi/dotfiles
```

2. Install the programs you are going to have dotfiles for if you have not done so already. If following this repo you should install the following:

- [Alacritty](https://github.com/alacritty/alacritty/blob/master/INSTALL.md)
- [Zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
- [Oh My Zsh](https://ohmyz.sh/#install)
- [Tmux](https://github.com/tmux/tmux/wiki/Installing)
- [LazyGit](https://github.com/jesseduffield/lazygit)

3. Run GNU stow to symlink the configs in dotfiles to their default locations:

```
cd dotfiles
stow .
```

## Reference

I found about this in [Dreams of Autonomy's video](https://www.youtube.com/watch?v=y6XCebnB9gs&pp=ygURZ2l0IHN0b3cgZG90ZmlsZXM%3D) so shout out to him!
