# What does I use?

- zsh
- oh-my-zsh
- powerlevel10k
- NerdFonts

# How to install?

## Install zsh

brief explanation of what is zsh

```bash
  sudo apt install zsh -y
```

or if you use Fedora

```bash
   sudo dnf install zsh -y
```

## Install oh-my-zsh

brief explanation of what is zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install powerlevel10k

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

## Install NerdFonts

To use the powerlevel10k theme you need to install a nerd font. The recommended is MesloLGS NF

- [MesloLGS NF Regular.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Regular.ttf)
- [MesloLGS NF Bold.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Italic.ttf)
- [MesloLGS NF Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold.ttf)
- [MesloLGS NF Bold Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold%20Italic.ttf)

dont forget to set the font in your terminal

## Install plugins

- autosuggesions plugin

  `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`

- zsh-syntax-highlighting plugin

  `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

- zsh-fast-syntax-highlighting plugin

  `git clone https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting`

- zsh-autocomplete plugin

  `git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git $ZSH_CUSTOM/plugins/zsh-autocomplete`

## Config your .zshrc

The file .zshrc is in your home directory, you can edit it with your favorite text editor

you can use my config or setup your own

[Download my .zshrc here](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/zshrc-exemple)

If you are lazy like me you can just copy and paste this command in your terminal

```bash
wget https://github.com/Raphael-Soares/workspace/raw/main/Terminal/zshrc-exemple
mv zshrc-exemple ~/.zshrc
```
