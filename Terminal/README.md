# Customizing Your Terminal Setup

Enhance your terminal experience with a curated selection of tools and configurations. It will look something like this:

![Terminal Screenshot]()

## Components Used:

- **zsh**: A powerful shell with enhanced features.

- **oh-my-zsh**: A delightful community-driven framework for managing zsh configurations.

- **powerlevel10k**: A highly customizable zsh theme for a visually stunning terminal.

- **NerdFonts**: Special fonts like MesloLGS NF to complement powerlevel10k.

## Installation Guide:

### Install zsh

Begin by installing zsh on your system. Choose the appropriate command based on your Linux distribution.

```bash
sudo apt install zsh -y   # Ubuntu/Debian
```

or

```bash
sudo dnf install zsh -y   # Fedora
```

### Install oh-my-zsh

Install oh-my-zsh with a simple one-liner.

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install powerlevel10k

Fetch powerlevel10k from its repository.

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

### Install NerdFonts

For powerlevel10k, install a recommended NerdFont, like MesloLGS NF.

- [MesloLGS NF Regular.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Regular.ttf)
- [MesloLGS NF Bold.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Italic.ttf)
- [MesloLGS NF Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold.ttf)
- [MesloLGS NF Bold Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold%20Italic.ttf)

Don't forget to set the font in your terminal.

### Install Plugins

Choose from a variety of plugins to enhance functionality.

- **autosuggestions plugin**

  ```bash
  git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
  ```

- **zsh-syntax-highlighting plugin**

  ```bash
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
  ```

- **zsh-fast-syntax-highlighting plugin**

  ```bash
  git clone https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting
  ```

- **zsh-autocomplete plugin**
  ```bash
  git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git $ZSH_CUSTOM/plugins/zsh-autocomplete
  ```

### Configure Your .zshrc

Edit the `.zshrc` file in your home directory with your preferred text editor. Use the provided example or create your own.

[Download the example .zshrc file here](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/zshrc-example)

For a quick setup, copy and paste this command in your terminal:

```bash
wget https://github.com/Raphael-Soares/workspace/raw/main/Terminal/zshrc-example
mv zshrc-example ~/.zshrc
```

Now you're all set to enjoy an enhanced terminal experience!
