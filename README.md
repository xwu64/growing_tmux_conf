# Growing tmux config

## INSTALL

```
$ git clone https://github.com/xwu64/growing_tmux_conf.git ~/.tmux
$ cd .tmux
$ git submodule init
$ git submodule update
$ mv ~/.tmux/.tmux.conf ~/
```

## Enable New Configuration

```
$ tmux source-file ~/.tmux.conf
```

## UPDATE plugins

```
$ cd ~/.tmux
$ git submodule add $URL$
$ git commit -m 'anything you want'
$ git push 
```
