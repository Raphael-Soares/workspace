# Customizing Your Terminal Setup

Enhance your terminal experience with a carefully curated selection of tools and configurations, resulting in a visually appealing setup as showcased below:

![Terminal Screenshot](https://raw.githubusercontent.com/Raphael-Soares/workspace/main/Terminal/%5B1%5D%20Print.png)

## Components Utilized:

- **zsh**: A robust shell enriched with advanced features.
- **oh-my-zsh**: A delightful community-driven framework for seamless management of zsh configurations.
- **powerlevel10k**: A highly customizable zsh theme offering a visually stunning terminal appearance.
- **NerdFonts**: Specialty fonts such as MesloLGS NF, complementing powerlevel10k.

## Installation Guide:

### Install zsh

Initiate the installation of zsh on your system. Choose the appropriate command based on your Linux distribution.

```bash
sudo apt install zsh -y   # Ubuntu/Debian
```

or

```bash
sudo dnf install zsh -y   # Fedora
```

### Install oh-my-zsh

Execute a simple one-liner to install oh-my-zsh.

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install powerlevel10k

Fetch powerlevel10k from its repository.

```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

### Install NerdFonts

For powerlevel10k, install a recommended NerdFont, such as MesloLGS NF.

- [MesloLGS NF Regular.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Regular.ttf)
- [MesloLGS NF Bold.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Italic.ttf)
- [MesloLGS NF Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold.ttf)
- [MesloLGS NF Bold Italic.ttf](https://github.com/Raphael-Soares/workspace/raw/main/Terminal/Fonts/MesloLGS%20NF%20Bold%20Italic.ttf)

Remember to set the font in your terminal.

### Install Plugins

Select from a variety of plugins to enhance functionality.

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

## Install eza and nala

In my configuration file, `apt` and `ls` are aliased to `eza` and `nala` respectively. To install them, run:

```bash
sudo apt install eza nala -y   # Ubuntu/Debian
```

or

```bash
sudo dnf install eza -y   # Fedora
```

## Change the terminal theme with GOGH

Choose a terminal theme that matches your desktop theme. I am currently using Gruvbox, which is 87, 88, or 89 in the list.

```bash
bash -c "$(wget -qO- https://git.io/vQgMr)"
```

Feel free to explore and customize your setup further to suit your preferences!
