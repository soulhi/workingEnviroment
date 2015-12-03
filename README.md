# workingEnviroment
When programming on linux/mac, here's some useful tools to improve your productivity.


## vim config
Vim is my favorite editor on linux/mac. It's powerful and very flexible, but when programming with vim, we still need
some features like searching file quickly, showing the code directory tree, etc.

#### Features
* show source code directory tree by plugin NERDTree
* find file quicking by plugin Ctrlp
* check python syntax by plugin flake
* mini buffer support by plugin minibufexpl
* source code tags generation by plugin easytags
Also, you could put the plugin interested in .vimrc by yourself, then install it.

#### Installtion guide:
1. install vundle:
   * git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

2. config the .vimrc, please backup your ~/.vimrc first!!!
   * git clone https://github.com/soulhi/workingEnviroment.git tmp
   * mv tmp/.vimrc ~/.vimrc

3. install ctags
   * on Linux: sudo apt-get install exuberant-ctags
   * on Mac: sudo brew install ctags

4. install vim plugin
   * open vim by type 'vim' in shell
   * run vim command ':PluginInstall', wait for vim to finish the installation

5. enjoy your vim

## screen config
#### Features:
* close the startup message when starting screen
* always show the opened window in message line which is at the bottom of the screen. This is very useful when switching between windows
 
#### Installtion guide:
config the ~/.screenrc, please backup your ~/.screenrc first!!!
* git clone https://github.com/soulhi/workingEnviroment.git tmp
* mv tmp/.screenrc ~/.screenrc

<!-- Markdown editor: https://jbt.github.io/markdown-editor -->
