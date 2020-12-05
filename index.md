---
layout: default
title: just-the-docs
nav_order: 1
---

# Just The Docs テーマ

[remotetheme.github.io](https://remotetheme.github.io/)

___

## Markdown の表示

[Markdown](markdown)

___

## _config.yml

`_config.yml` は次の情報を入れます。

```
theme: jekyll-theme-leap-day
lang: ja
title: Leap Day テーマ
description: GitHub Pages Leap Day テーマ.
show_downloads: false
google_analytics: UA-OOOOOOOO-O
```

```
theme: jekyll-theme-leap-day
```

このテーナ **Leap Day** を使用する場合に指定します。

```
lang: ja
```

**日本語** の場合はこれを含めて下さい。 `<html lang="ja">` へ変換されます。

```
title: Leap Day テーマ
description: GitHub Pages Leap Day テーマ.
```

ヘッダに表示されます。省略した場合はリポジトリ名・タグが反映されます。

```
show_downloads: false
```

ダウンロードを使用しない場合は **false** にします。\
**true** の場合はリポジトリの **Releases** で公開している最新版の\
`.zip` および `.tar.gz` ファイルがダウンロード表示になります。

```
google_analytics: UA-OOOOOOOO-O


Google アナリティクス の トラッキング ID を入れると、\
ソースにトラッキングコードが付与されます。\
Google アナリティクス 4 のコードは非対応です。

___

## サイドバー

見出し h1～h3 の一覧を自動生成します。

実際のテーマではスクロールしても固定表示になっていますが、\
[markdown](markdown) ページの見出し項目が多く、固定表示では問題があるため、\
ここではスクロールするようにカスタム CSS を適用しています。

___

[remotetheme.github.io](https://remotetheme.github.io/)

