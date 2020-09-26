# Repository to test Jekyll and its functionality


### install
install gem if needed
```
sudo apt-get install ruby-full build-essential zlib1g-dev
```

add to `.bashrc`
```bash
# Install Ruby Gems to ~/gems' >> ~/.bashrc
export GEM_HOME="$HOME/gems"' >> ~/.bashrc
export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
```

install jekyll (it takes a while)
```bash
~$ gem install jekyll bundler
```

*Note*: I hade problems in doing ```source .bashrc``` with zsh, no prob with bash
