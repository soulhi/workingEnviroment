# workingEnviroment
When programming on linux/mac, here's some useful tools to improve your productivity.


------------------------- config vim -------------------------

Vim is my favorite editor on linux/mac. It's powerful and very flexible, but when programming with vim, we still need 
some features like searching file quickly, showing the code directory tree, etc. 

Here's my vim configuration, after installing it, you'll get the vim plugin:
* show source code directory tree by plugin NERDTree
* find file quicking by plugin Ctrlp
* check python syntax by plugin flake
* mini buffer support by plugin minibufexpl
* source code tags generation by plugin easytags
Also, you could put the plugin interested in .vimrc by yourself, then install it.

Here's the installtion guide:
1. install vundle 
   git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

2. config the .vimrc, please backup your ~/.vimrc first!!!
   git clone https://github.com/soulhi/workingEnviroment.git tmp
   mv tmp/.vimrc ~/.vimrc

3. install ctags
   on Linux: sudo apt-get install exuberant-ctags
   on Mac: sudo brew install ctags

4. install vim plugin
   4.1 open vim by type 'vim' in shell
   4.2 run vim command ':PluginInstall', wait for vim to finish the installation

5. enjoy your vim

