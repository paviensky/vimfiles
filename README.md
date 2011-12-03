# Usage
```bash
git clone git://github.com/paviensky/vimfiles.git ~/.vim
cd ~/.vim
git submodule init
git submodule update

ln -s ~/.vim/vimrc ~/.vimrc
```

## Command-T

Command-T plugin has to be installed (with default Ruby) as

```bash
# rvm use system
cd ~/.vim/bundle/command-t/ruby/command-t
ruby extconf.rb
make
```
