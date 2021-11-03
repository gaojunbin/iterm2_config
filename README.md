# ITerm2 配置

1. Download ITerm2 at [https://iterm2.com](https://iterm2.com)

2. install oh-my-zsh

   ```bash
   git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
   cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
   ```

3. set ZSH_THEME in .zshrc file to choose the theme，here we set：agnoster

4. install powerline fonts

   ```shell
   # clone
   git clone https://github.com/powerline/fonts.git
   # install
   cd fonts
   ./install.sh
   ```

5. Open ITerm2-Preferences-Profiles-Text

   + Tick use a different font for non-ASCII text
   + chose Meslo LG L DZ for Powerline as the font of Font and non-ASCII text

6. intall aoto-filled

   + download  http://mimosa-pudica.net/src/incr-0.2.zsh
   + mv it to `~/.oh-my-zsh/custom/plugins/incr/incr-0.2.zsh`
   + Add `source $ZSH/custom/plugins/incr/incr*.zsh` to the file `.zshrc`