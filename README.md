# autoinstall_init
macOS, Linux afterinstall scripts


# macOS

#show hidden files

```defaults write com.apple.Finder AppleShowAllFiles true```
```killall Finder```

#disable gatekkeper

```sudo spctl --master-disable`

#add spaces for Dock

```defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'```
```killall Dock```

#homebrew 

```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

#essensial

```brew install zsh zsh-completions```
```curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh```
```chsh -s /usr/local/bin/zsh```

```Brew install wireshark```
```Brew cask install wireshark```

```Brew install nmap```

```Brew install python3```

```Brew install wget```

```Wget https://bootstrap.pypa.io/get-pip.py```
```python get-pip.py --user```

```Brew install python```
```python -m pip install --upgrade --force-reinstall pip```


#PGP

```https://gpgtools.org/```

#HEX editor

```http://www.suavetech.com/0xed/```

#diff

```https://www.kaleidoscopeapp.com/```

#code

```https://code.visualstudio.com/```

#quicklook

```brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize webpquicklook suspicious-package quicklookase qlvideo```

```brew cask install provisionql```

```brew cask install quicklookapk```
