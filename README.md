Windowsの各種設定ファイル

以下がファイルの構成
~~~
|-.gvimrc
|-.minttyrc
|-.vimrc
|-.zshenv
|~Dropbox (smartnova)
| |~lib/
| | |+git/
| | |+vim/
| | |+zsh/
|~.tmp
| |~vim
| | |~backup
| | |~undo
~~~

vimの設定で~/.tmp/vim/{backup, undo}を時ファイル置き場などに使っているので、これらを事前に作成すること。

~~~
mkdir -p ~/.tmp/vim/{backup,undo}
~~~
