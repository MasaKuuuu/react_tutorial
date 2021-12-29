# react_tutorial

こちらを参考に入門

* 今から始めるReact入門 〜 React の基本
  * https://qiita.com/TsutomuNakamura/items/72d8cf9f07a5a30be048

# WSL2 で開発用サーバを立ち上げるコマンド

webpack のバージョン

```
masaki@DESKTOP-IU10L8A:~/study/react/react-tutorial$ webpack -v
webpack: 5.65.0
webpack-cli: 4.9.1
webpack-dev-server 4.7.1
```

mode を設定していないと Worning が発生してWebサーバが立ち上がらないため以下のオプションを指定する

```
webpack serve --mode=development
```

# メモ

サーバは `/public` に配置しているファイルが公開されるため、index.html の配置場所を変更する