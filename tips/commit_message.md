# コミットメッセージの書き方

* 1行目：変更内容の要約（タイトル、概要）
* 2行目 ：空行
* 3行目以降：変更した理由（内容、詳細）

## コミットメッセージの規則

別に強制的なルールがあるわけではないが、コミットメッセージに統一的な規則があると、メッセージに悩む時間を減らせるし、後にコミットを振り返るときにわかりやすいので推奨。

コミットメッセージは次の構造をとるようにする。

> `[hoge]piyo`

`hoge`の部分にはコミット内容の種類、`piyo`の部分はコミットの内容を短く書くことにする。また、必要に応じて詳細なコメントを追加する。

### コミット種別

* `add`: 新規ファイルのトラッキングを開始
* `fix`: エラー、バグ回避のための修正
    * `hotfix`: 重要、大規模な修正
* `change`: 仕様変更（機能には影響を及ぼさない程度）
* `clean`: 整理（スペースやインデント）
    * `disable`: 無効化（コメントアウト等）
* `merge`: ファイルの統合
* `modify`: 修正（表現、表記など）
* `move`: 移動
    * `remove`: 削除
    * `rename`: 名称変更
* `tmp`: 一時的なものに対して
* `upgrade`: 機能追加、加筆

絵文字をコミットメッセージに含めたり、省略形として用いるのも良い手段だと思う。

ref)
* [Gitのコミットメッセージの書き方 - Qiita](http://qiita.com/itosho/items/9565c6ad2ffc24c09364)
* [Gitのコミットメッセージを絵文字から始める - Qiita](http://qiita.com/pocotan001/items/775cc77087be5562cc56)
* [コミットメッセージのルール - Opacities](http://sadakoa.hateblo.jp/entry/2014/11/22/185947)
* [英語コミットコメントに使えるオシャレフレーズ集]( http://ift.tt/1cyfHqg)
* [変更を記録するコミッ](http://www.backlog.jp/git-guide/intro/intro1_3.html)
* [git commit時のコメントを英語で書くための最初の一歩](http://www.sssg.org/blogs/hiro345/archives/11721.html)
* [クリアなコードの作り方: 意図が伝わるコミットのしかた](http://www.clear-code.com/blog/2012/3/13.html)
* [提言: コミットメッセージの一行目には要求仕様を書け](http://qiita.com/magicant/items/882b5142c4d5064933bc)
* [[翻訳] 私のコミットをまとめないで](http://qiita.com/gogotanaka/items/8c55f69120965b077737)
* [コミットメッセージの先頭に絵文字いれるのが流行ってんだろうか](http://ift.tt/1r2xhYk)
