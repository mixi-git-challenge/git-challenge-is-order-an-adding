# 問題: なぜか新しいファイルを追加できないリポジトリ

ある顧客情報を git のリポジトリで管理しています。
新しいリストのファイルを追加することになったのですが、なぜか新しいファイルをリポジトリに追加できません。

追加したいファイルをどうにかしてリポジトリに追加してください。
追加できない原因を解消してもしなくても構いません。


## 追加したいファイルについて

追加したいファイルは `users4.csv` というファイルです。

[ダウンロードリンク](https://gist.githubusercontent.com/kikuchy/7d0a52299707005ecbd3/raw/3ac45a2b7d1fa7ad725ca2c9d5d84d9f45b11faa/users4.csv)からダウンロードするか、以下のコマンドで入手してください。

```
curl https://gist.githubusercontent.com/kikuchy/7d0a52299707005ecbd3/raw/3ac45a2b7d1fa7ad725ca2c9d5d84d9f45b11faa/users4.csv > users4.csv
```


## 正答条件

* `master` ブランチに `users4.csv` をコミットして origin に push してください
* 余計なファイルを含んではいけません