# Setting up a Kristen Approved Development Environment(Mac)

## OS Changes
### General
- Enable automatically hide and show the menu bar

### Dock
- Enable automatically hide and show the Dock

### Mission Control
- Disable automatically rearrange Spaces based on most recent use

### Keyboard
- Keybord -> Modifier Keys
  - Caps Lock -> Control

### TrackPad
- Point & Click
  - Enable Secondary Click with click or tap with two fingers
  - Enable tap to click with one finger
  - Click
    - Medium
  - Tracking Speed
    - Second Fastest

### Menubar
- Show battery percentage
___

## Tools
- [Chrome](www.google.com/chrome)
- [iTerm](https://www.iterm2.com/downloads.html)
- [Atom](https://atom.io/)
- [Spectacle](https://www.spectacleapp.com/)
- [Übersicht](http://tracesof.net/uebersicht-widgets/)(Background widgets, optional)

### iTerm Setup
#### Profile
- import `iterm-profile/com.googlecode.iterm2.plist` to iTerm for colors

#### Terminal Tools
0. install command line tools
- `xcode-select --install`
1. install Homebrew  
  - ` /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. install Vim
  - `brew install vim`
3. install Git
  - `brew install git`
4. install Zsh
  - `brew install zsh zsh-completions`
5. install Node and npm
  - `brew install node`

### Atom
- Theme — nucleus-dark-ui
- Packages:
  - editorconfig
  - file-icons
  - languages:
    - language-babel
    - language-gradle
    - language-groovy
  - multicursor

### Oh-My-Zsh
- install Oh-My-Zsh
  - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`  
- put  `variant.zsh-theme` in the `.oh-my-zsh/themes` directory
- change the shell `chsh -s /bin/zsh`

#### Edit .zshrc
- current plugins `git zsh-autosuggestions osx zsh-syntax-highlighting`
