# 安装Vundle
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`
`vim +PluginInstall +qall`

# 安装cmake
`brew install cmake`

# 编译YCM
`cd ~/.vim/bundle/YouCompleteMe`
`git submodule update --init --recursive`
`python install.py`

# 拷贝配置
`cp ~/.vim/bundle/YouCompleteMe/third_party/ycmd/examples/.ycm_extra_conf.py ~/`
