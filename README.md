# doc_github_pages_deploy
## 概要
- ドキュメントをブランチ別のファイル名でGitHub Pagesにデプロイする

## 詳細
- 下記のブランチにpushすると `original/source.html` を `ブランチ名.html` として `gh-pages` ブランチにpushする
  - master
  - develop
- つまり、`develop.html`, `master.html` が `gh-pages` ブランチに作成されます

## 使い所
- master, developの2つのブランチが存在する
- master, developでドキュメントをビルドしている
- master, developそれぞれのドキュメントを閲覧したい

## 注意
- `gh-pages` ブランチにはあらかじめ `index.html` を配置しておく必要がある
  - 本リポジトリではmasterにある `docs/index.html` を配置済み
