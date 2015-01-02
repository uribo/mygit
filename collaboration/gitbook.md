# GitBook

[GitBook](https://github.com/GitbookIO/gitbook)は、マークダウンで記述した複数のファイルをGithub/Git上にリポジトリとしてまとめ、本のような形で公開できる。

NPMを使ってインストールする

`npm install gitbook -g`

## 出力形式

GitBookで作成したドキュメントは次のフォーマットに出力可能。

* 静的ウェブサイト
* PDF
* eBook
* JSON

## 構成要素

リポジトリ内に少なくとも以下の２つのファイルが必要。

* `README.md`...概要について説明をする
* `SUMMARY.md`...目次となる

## GitBookエディターの使用

[editor](https://github.com/GitbookIO/editor)はWindows, Linux, Macのプラットフォームに対応しており、目次を見ながら編集できるので楽に執筆ができる。

File -> New Book -> フォルダを選択

## 細かなこと

### 目次、章の作成

`README.md`と同じフォルダに`SUMMARY.md`を置き、そのファイル内で本の構成を決める。

### 画像の挿入

画像ファイル用のフォルダを用意し、markdownファイル中でディレクトリを指定して表示させる。assetsフォルダ内にある`img.png`を挿入したい場合は`![](../assets/img.png)`とする。

### ページ間のリンク

目的のファイルへのパスをリンクとする（markdown）。すなわち、`[リンク](../chapter2/readme.md)`。

