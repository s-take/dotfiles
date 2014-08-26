dotfiles
========

.vimrc使うとき

```
$ mkdir -p ~/.vim/bundle
$ git clone git://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim

$ sudo yum install -y lua lua-devel
$ sudo yum groupinstall -y 'Development tools'
$ sudo yum install -y ncurses ncurses-devel
$ sudo yum install -y mercurial

$ cd /usr/local/src
$ sudo hg clone https://vim.googlecode.com/hg/ vim
$ cd vim
$ sudo ./configure --enable-multibyte --with-features=huge \
--disable-selinux --prefix=/usr/local \
--enable-luainterp=yes --with-lua-prefix=/usr
$ sudo make && sudo make install
$ alias vim="/usr/local/bin/vim"
```
