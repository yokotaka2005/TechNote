# 自分のGitの使い方メモ
## ファイルを追加した場合
File-add.jsを追加した場合

    $ git add File-add.js  <--ステージングする
    $ git status  <--現状の状態を確認、追加ファイルが含まれているか確認
    $ git commit  <--ステージングした内容をコミット
    $ git push  <--GitHubのリポジトリにアップロード

## 作業を行う場合
作業用のブランチを作成して修正を行っていく。

    $ git branch  <--現在のリポジトリのブランチの一覧を確認
    $ git branch branch_sample  <--作業用のブランチを作成する
    $ git checkout branch_sample <--作業用のブランチにカレントブランチを切り替える

作業を進めていく