# dotfiles

## iTerm Customisation

![](https://screenshot.click/D-24-ukfhd-omia3.jpg)

* _Features:_
    * Shopify theme colors
    * abbreviated working folder location
    * git branch name
    * git working tree indicator (untracked files = blue, unstaged files = red, staged files = yellow, committed files - green)
    * git commit status indicator (ahead or behind of origin and by how many commits)

### Shopify Colors

1. Download the `iterm-customisation/colors/shopify.itermcolors` file
1. In iTerm2 go to `preferences > profiles > colors > color presets` and import the file to use the color theme

### Git Prompt

1. Download the `iterm-customisation/themes/shopify.zsh-theme` file
1. Copy it to your themes folder (typically located at `~/.oh-my-zsh/themes`
1. Open up your ZSH config file (typically located at `~/.zshrc`
1. Find the config value `ZSH_THEME`. By default it will be `ZSH_THEME="robbyrussell"`
1. Change the value to be `ZSH_THEME="shopify"`
1. In terminal run `. ~/.zshrc` to restart your terminal shell
