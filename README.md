# Portfolio

## Portfolioとは
CSSのフレームワークを使うために、練習で簡単なportfolioを作成する。

## インストール

### 要件
 - git >= version 2.17.1
 - HTML5
 - CSS3 FW(Bootstrap4)


## 開発方針

### 開発フロー
開発を行うときは、以下の手順に沿ってください。
1. issueを作成、修正するissueを選択する　(GitHub)
1. issueブランチの作成 (下記のブランチ作成を参照)(GitHub)
1. ローカルリポジトリでリモートの変更点を更新 <br>`git fetch`
1. ローカルリポジトリでリモートで作ったブランチを作成<br>`git checkout -b lcl-ローカルブランチ名 origin/リモートブランチ名`
1. ブランチ確認<br>`git branch`<br>
5.1 ブランチが作成したブランチと異なる場合はブランチを変更する<br>`git checkout 変更したいブランチ名`
1. 変更が完了したら `git add . `で変更点を追加
1. コミット(ファイルの変更をローカルgitリポジトリに保存)<br>`git commit -m "変更内容を記載"`<br>
(-m)とは commit のオプションでコメントするよ。って意味
1. コミットした内容をリモートリポジトリにpush<br>`git push origin HEAD:リモートブランチ名`
1. マスターブランチへのプルリクエストの作成
1. コードレビュー者によるレビュー
1. マスターブランチへマージ

### デフォルトブランチ
`master`:コードレビューが完了したら、ここにマージします。


### ブランチを作成
ブランチを作成するときは、以下のブランチ名形式に従ってください。

```
// Branch Name Format
[issue no]-[branch name]

//sanple
1-create-apple
```


