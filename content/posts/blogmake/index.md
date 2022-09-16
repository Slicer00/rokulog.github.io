---
title: "GitHub PagesとHUGOを使ってブログを開設"
date: 2022-09-13
categories: ["ブログ"]
tags: ["ブログ作成", "go", "markdown"]
menu: main
---

<!-- menu: mainを使うとトップバーに固定される -->

### 当サイトを開設した理由

- 自分が言語や映像などで勉強したことの保管場所が欲しかった。
- 学んだことをポートフォリオとして形に残したい。
- マークダウンやブログ開設について学びたかった。
### 今回したこと

ほとんどこの方のZennに書いてある通り進めた。

<a href="https://zenn.dev/kato_k/articles/66531db0c4024d">kato_kさんのZenn</a>

つまずいた所を書いておく。

### config.tomlファイルでリンク先を指定

これをしなかったらhtmlが直で表示されてしまい、CSSが適用されていなかった。
先にconfig.tomlファイルを編集しておくことを推奨したい。