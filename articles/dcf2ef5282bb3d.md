---
title: "Zennでいっぱい記事書きたいから、まずはGitHub連携をしてみる"
emoji: "㊗️"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["GitHub","Zenn"]
published: true
---

思ったより簡単だった。
感謝……。

何番煎じって感じだけども、せっかくなので記事を書いてみます。

# 手順

## GitHubでリポジトリを作成

https://zenn.dev/zenn/articles/connect-to-github

公式による上記記事の「GitHubとの連携手順」を実施。

## Zenn CLIの導入

https://zenn.dev/zenn/articles/install-zenn-cli

* Node.jsの18.17.0 LTSをインストール。
* 上記記事の「Zenn CLIの導入手順」を実施。

## 記事を書く

https://zenn.dev/zenn/articles/zenn-cli-guide

* 上記記事の「記事の作成」を実施。ファイルが出来上がる。
* 上記記事の「プレビューする」を実施。ブラウザから開くとこんな感じ。

![](https://storage.googleapis.com/zenn-user-upload/4e0a9efae238-20230806.png)

* 左メニューの「画像のアップロード」から画像をアップロードし、URLを取得し、記事に入れることで、画像を載せられる。（画像をフォルダー内に置く方法もあるらしい。そちらは左メニューの「画像管理ガイド」を参照）

* 記事を保存すると、プレビューも自動で更新される。

## 記事を公開する

https://zenn.dev/zenn/articles/zenn-cli-guide

* 上記記事の「記事を公開する」を実施。
* 予約投稿なども可能。詳細は上記の記事を参照。

# ハマったとこ・気をつけるべきこと

* リポジトリつくってSourceTree上で開いたら、「masterブランチがないが？」と怒られ、GitHub上からmainブランチをリネームした。その際、一個もファイルがないとリネームできなかったぽいので、適当なファイルをコミットした。もっとうまい方法がある気がする。（これはもはやZenn関係ない）
* Gitやターミナルにあんまり慣れていなくて、もたもたしてしまった。（これもZenn関係ない）この機会に慣れていきたい。

# よかったこと

* CLIでいくつかコマンドを打つと、勝手にフォルダー構成をなんとかしてくれるので、その辺は楽だった。
