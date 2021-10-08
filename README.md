# 囲みマス プロジェクト

kakomimasu Organizationに属するリポジトリ共通の決め事などを記載しています。

## セマンティック バージョニング 2.0.0

各リポジトリは[セマンティック バージョニング](https://semver.org/lang/ja/)を実践しています。各リポジトリにてリリースを行う際にはこれに従ってください。

## `CHANGELOG.md`

各リリースにおける変更点については`CHANGELOG.md`に記載するとします。`CHANGELOG.md`の書き方については[Keep a Changelog](https://keepachangelog.com/ja/1.0.0/)を参考にしてください。

## リポジトリ共通設定

新たに作成したリポジトリには以下の設定を行うことをお勧めします。

- デフォルトブランチ名は`main`
- `main`ブランチにBranch protection ruleを設定する。
    - `Settings`->`Branches`->`Branch protection rules`
    - `Branch name pattern` は `main`
    - `Require a pull request before merging`にチェック
- PRマージ時に自動でブランチを削除する。
    - `Settings`->`Options`
    - `Automatically delete head branches`にチェック