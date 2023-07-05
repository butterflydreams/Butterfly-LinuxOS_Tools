# Oh-My-Zsh
[![CI](https://github.com/ohmyzsh/ohmyzsh/workflows/CI/badge.svg)](https://github.com/ohmyzsh/ohmyzsh/actions?query=workflow%3ACI)

## USAGE
To learn more, visit [ohmyz.sh](https://ohmyz.sh), or follow [@ohmyzsh](https://twitter.com/ohmyzsh) on Twitter.

## INSTALLATION
Oh My Zsh is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl`, `wget` or another similar tool.

| Method    | Command                                                                                |
| :-------- | :------------------------------------------------------------------------------------- |
| **curl**  | `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |
| **wget**  | `sh -c "$(wget -O- https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`   |
| **fetch** | `sh -c "$(fetch -o - https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` |

## THEMES
- https://github.com/ohmyzsh/ohmyzsh/wiki/Themes  
- ### Configuration
  In order to enable a theme, set ZSH_THEME to the name of the theme in your `~/.zshrc`, before sourcing Oh My Zsh; for example: ZSH_THEME=robbyrussell If you do not want any theme enabled, just set ZSH_THEME to blank: ZSH_THEME=""
- ### Customization
  1、 Download theme file, such as [butterfly.zsh-theme](./butterfly.zsh-theme).  
  2、 Move theme file to `~/.oh-my-zsh/themes` directory.  
  3、 Edit `~/.zshrc` configruation, set ZSH_THEME=your theme.  
  4、 Touch the command `source ~/.zshrc` to make it effect.  

## PLUGINS
- ### [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#installation)

