## My Dev Setup: Terminal + Shell

I am a sucker for a good dev setup for both my terminal and my editor. So in this post, I shall be writing about the Terminal and shell parts of my dev setup.

# *Terminal*

My terminal emulator is  [iterm2](https://iterm2.com/). This has all the good features like multi-pane, multi-tab and auto-complete support.


![terminal.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1599057395431/zssjbny55.png)

# *Shell*

I use  [zsh](https://ohmyz.sh/)  as my shell. The reason behind using zsh is the support for some very good plugins + powerful auto-complete features + great set of aesthetic themes to choose from.

Similar to a `.bash_profile` , Zsh has a `.zshrc` file where all your zsh settings and configurations are saved.

Zsh has a  [lot of themes](https://zshthem.es/all/)  to choose from. Being a frequent git user, I went with the [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme. This needs to be specified in the `.zshrc` file for the `ZSH_THEME` variable

![Agnoster.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1599058695384/js4BvkxuK.png)

I use the  [Solarized Dark](https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) preset. You can select it from the color preset tab in the Zsh preferences menu


![color_preset.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1599058478029/eL4ST4ibv.png)

I use the `Cousine for Powerline` font. For using this, the  [powerline fonts](https://github.com/powerline/fonts)  repository has to be downloaded and the fonts have to be installed


![Font.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1599058865704/I5UdxWCq0.png)

For zsh to auto-complete your scripts or code, they should be added to the  `plugins` list in the `.zshrc` file. As I only use git, python, and bash mostly, I have added them.  (`zsh-syntax-highlighting` helps me with the syntax prompts. It is straightforward, as in the font color is red if the syntax is wrong, and green if the syntax is correct)

![plugins.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1599059177891/4dAY_6zhk.png)

My terminal settings and theme(s) complement my VS Code themes and settings very nicely. I shall write about my VS Code setup in the next post. 

Hope you liked this article :)
