# Ironman Reactor - Übersicht widget

This is an [Übsersicht widget](http://tracesof.net/uebersicht/) which shows an Ironman Reactor with rotating coils in your desktop.

I did it following [this awesome tutorial](https://css-tricks.com/iron-mans-arc-reactor-using-css3-transforms-and-animations/) from [CSS Tricks](https://css-tricks.com/).

## Easy Installation if you have Homebrew and Git:
```bash
brew tap caskroom/cask &&
brew cask install ubersicht &&
git clone https://github.com/Dellos7/ironman-reactor-ubersicht-widget.git $HOME/Library/Application\ Support/Übersicht/widgets/ironman-reactor-ubersicht-widget &&
open /Applications/Übersicht.app

# For easy access to the widgets folder:
cd $HOME/Library/Application\ Support/Übersicht/widgets

# How to easily shut of Übersicht
osascript -e 'quit app "Übersicht"'

# Easy uninstall the plugin:
rm -rf $HOME/Library/Application\ Support/Übersicht/widgets/ironman-reactor-ubersicht-widget
```
## Screenshot

![Ironman Reactor Screenshot](screenshot_gh.png)

## Rotating coils gif

![Ironman Reactor rotating coils gif](ironman-reactor.gif)
