# .config

## Installation

**Iterm 2**
```shell
# Install Iterm
brew cask install iterm2

# Update to material design color scheme
cd Downloads
curl -O https://raw.githubusercontent.com/MartinSeeler/iterm2-material-design/master/material-design-colors.itermcolors

### Manually ###
# Go to iTerm2 > Preferences > Profiles > Colors Tab -> Color Presets… -> Import…
```

**ZSH**
```
# Install zsh
brew install zsh 

# Install oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# Install zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

**File transfer**

Move the .zshrc, .vimrc and .p10k.zsh files to the `$HOME` directory
```shell
git clone https://github.com/chrispduck/.config.git
cd .config
cp .zshrc .vimrc .p10k.zsh $HOME
```

