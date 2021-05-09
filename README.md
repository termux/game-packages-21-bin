# Termux binary package repository

![GitHub repo size](https://img.shields.io/github/repo-size/termux/game-packages-21-bin)

Read-only repo containing the packages built for android 5, that were
previously hosted on bintray.com. 

To be able to install these packages in termux for android 5 you need
to edit `$PREFIX/etc/apt/sources.list.d/game.list` and change from:

```
deb https://dl.bintray.com/grimler/game-packages-21 games stable
```

to

```
deb https://termux.com/game-packages-21-bin games stable
```
