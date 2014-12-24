Sublime Text 3 Settings
==============================


Installation
------------

###Mac&Win共通設定

1. Sublime Text 3を起動
2. Package Controll をインストール（View -> ShowConsole）  
[Package Controll Plugin](https://sublime.wbond.net/installation)

###Mac OSX
```shell-session
$ cd ~/Library/Application Support/Sublime Text 3/
$ git init
$ git remote add origin git@github.com:hisashi0929/sublime-text-3.git
$ git pull origin master
```

###Windows
```shell-session
$ cd ~/AppData/Roaming/Sublime\ Text\ 3/
$ git init
$ git remote add origin git@github.com:hisashi0929/sublime-text-3.git
$ git pull origin master
```

注意：WindowsではEmmet Pluginが正しく動作しない可能性があるので、その際は下記を手動ダウンロードして  
[PyV8](https://github.com/emmetio/pyv8-binaries)


Reference
---------
* [SublimeText2 - Sublime Text2,3のDropbox, Gitを使った同期の方法 - Qiita](http://qiita.com/matsu_chara/items/b58564bba37e81637057#windowsvista%E4%BB%A5%E9%99%8D%E3%81%AE%E5%A0%B4%E5%90%88)	
* [SublimeTextの設定をgit管理し、複数PCで設定やパッケージを同期する。 - MANA-DOT](http://blog.manaten.net/entry/sublimetext-git)
* [Sublime Text 3 のプラグインと設定を Git で共有してみた - rakugaki-box.net](http://blog.rakugaki-box.net/entry/2014/11/16/sublime_git)