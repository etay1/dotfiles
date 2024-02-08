# Dotfiles

This repository contains the dotfiles for Etay1, including configurations for Zsh.

## Zsh Configuration

This repository includes configurations for Zsh. The main configuration file is `.zshrc`.

### Plugins

I use both [Oh My Zsh](https://ohmyz.sh/) and [Zplug](https://github.com/zplug/zplug) for managing plugins and themes.

- **Oh My Zsh Plugins:** The list of plugins managed by Oh My Zsh can be found in the `.zshrc` file under the `plugins` section.
- **Zplug Plugins:** The list of plugins managed by Zplug can be found in the `.zshrc` file under the `zplug` section.

### Theme

I'm using the [Powerlevel10k](https://github.com/romkatv/powerlevel10k) theme for Zsh. You can customize the theme according to your preference in the `.zshrc` file.

## Customization

Feel free to customize any of the configurations to suit your preferences. You can edit the `.zshrc` file directly or add additional configuration files as needed.

## Installation

To use these dotfiles, follow these steps:

```bash
# Clone the repository to your home directory:
git clone https://github.com/etay1/dotfiles.git ~/.dotfiles

# Navigate to the cloned repository:
cd ~/.dotfiles

# Symlink the `.zshrc` file to your home directory:
ln -sf ~/.dotfiles/.zshrc ~/.zshrc

# Install Zplug:
curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh

# Restart your terminal or run `source ~/.zshrc` to apply the changes.

