# Macbook Development Setup Guide
This repository records how I setup and configure my macbook for the engineering work.

## Homebrew
install homebrew

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

tell the system to use programs installed by homebrew (in /usr/local/bin)

    echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile
test

    brew doctor
homebrew usage

    brew install [package]
    brew update
    brew outdated
    brew upgrade [package]
    brew cleanup
	brew list --versions

## Homebrew Cask
install homebrew Cask

	brew tap caskroom/cask
	brew install brew-cask

brew cast usage

	brew cask search
	brew cask install alfred

### git
install git

    brew install git

configure

    git config --global user.name "Your Name Here"
    git config --global user.email "your_email@youremail.com"

## iTerm2 + zsh
install iTerm2+zsh

	brew cask install iTerm2

configure iterm2
    Keys -> show/hide iTerm2 with a system-wide hotkey: Command+Option+i
    Terminal -> silence bell

configure iterm color and fonts
download solarized color scheme at http://ethanschoonover.com/projects and then Colors -> Load Presets

## Sublime
install sublime

    brew cask install sublime

configure sublime as the sublime.config file shows
create a shortcut to open sublime from command line

    ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl


