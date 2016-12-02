# Homebrew

Package managers make it so much easier to install and update applications (for Operating Systems) or libraries (for programming languages). The most popular one for OS X is [Homebrew](http://brew.sh/).

### Install

An important dependency before Homebrew can work is the **Command Line Tools** for **Xcode**. These include compilers that will allow you to build things from source.


We can install Hombrew! In the terminal paste the following line (without the `$`), hit **Enter**, and follow the steps on the screen:

    $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

One thing we need to do is tell the system to use programs installed by Hombrew (in `/usr/local/bin`) rather than the OS default if it exists. We do this by adding `/usr/local/bin` to your `$PATH` environment variable:

    $ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile

Alternatively, we can also insert `/usr/local/bin` to the first line of `/private/etc/paths` and reboot the Mac to change global paths loading order. Admin password may be required if you modify the file.

Open an new terminal tab with **Cmd+T** (you should also close the old one), then run the following command to make sure everything works:

    $ brew doctor
    
    
  brew install vim
  brew install python
  brew install pyenv
  brew cask install java
  brew install rbenv ruby-build rbenv-default-gems rbenv-gemset
  echo 'bundler' >> "$(brew --prefix rbenv)/default-gems"
  brew update
  brew install node
  brew install maven
  brew install mysql
  brew services start mysql
  brew services stop mysql
  brew services start mysql
  brew install ack
  brew install bash-completion
  brew install htop
  brew install tree
  brew install wget
  brew install vimpager
  brew install ffmpeg
  brew list
  brew info vnstat
  brew info lftp
  brew info dark-mode
  brew install dark-mode
  brew install p7zip
  brew info git-lfs
  brew install z grc
  source "`brew --prefix`/etc/grc.bashrc"
  brew cask install xquartz
  brew install wine  
