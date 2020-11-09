# インストール手順

まず、ホームディレクトリにPullする。

```
git pull
```

シンボリックリンクを貼るので、既存の設定ファイルを削除しておく。

```
rm ~/.vimrc
rm ~/.tmux.conf
```

シンボリックリンクを貼る

```
ln -s ~/dotfiles/.vimrc ~/.vimrc
ln -s ~/dotfiles/.tmux.conf ~/.tmux.conf
```

vim-plugのインストールを忘れずに。

https://github.com/junegunn/vim-plug

