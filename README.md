# SimpleBrowser

Simple WebEngine Qt Browser.

## Build

### Dependences for Loongnix

```
sudo apt-get install qtwebengine5-dev
```


```
$ qmake simplebrowser.pro
$ make -j4
# make install
```

## FAQ

* Why could not input Chinese Simplifed in SimpleBrowser?
  Install `fcitx-frontend-qt5` and edit `~/.xprofile`:
  ```
  export GTK_IM_MODULE=fcitx
  export QT_IM_MODULE=fcitx
  export XMODIFIERS=@im=fcitx
  ```
