---
layout: default
title: Just The Docs テーマ
nav_order: 1
---

# Just The Docs テーマ

[remotetheme.github.io](https://remotetheme.github.io/)

___

## _config.yml

`_config.yml` は次の情報を入れます。

```
remote_theme: pmarsceill/just-the-docs
lang: ja
title: Just The Docs
description: GitHub Pages Just The Docs テーマ
logo: "/assets/images/just-the-docs.png"
search_enabled: true
aux_links:
  "GitHub ソース":
    - "https://github.com/remotetheme/just-the-docs"
footer_content: 
ga_tracking: UA-OOOOOOOO-O
```

```
remote_theme: pmarsceill/just-the-docs
```

このテーマ **Just The Docs** を使用する場合に指定します。

```
lang: ja
```

**日本語** の場合はこれを含めて下さい。 `<html lang="ja">` へ変換されます。

```
title: Just The Docs
```

左上に表示されます。

```
description: GitHub Pages Just The Docs テーマ
```

Just The Docs では表示されませんが、meta タグに含まれます。

```
logo: "/assets/images/just-the-docs.png"
```

画像表示になります。

```
search_enabled: true
```

本文上に検索バーを表示します。

```
aux_links:
  "GitHub ソース":
    - "https://github.com/remotetheme/just-the-docs"
```

右上のリンクを設定します。

```
footer_content: 
```

左下に表示します。

```
ga_tracking: UA-OOOOOOOO-O
```

Google アナリティクス の トラッキング ID を入れると、\
ソースにトラッキングコードが付与されます。\
Google アナリティクス 4 のコードは非対応です。

他にも設定があります。

<https://pmarsceill.github.io/just-the-docs/docs/configuration/>

___

## サイドバー

左サイドバーにはページの一覧を表示します。\
表示順は `nav_order` で設定できます。

```
---
layout: default
title: just-the-docs
nav_order: 1
---
```

___

## テーマのプロジェクト・ソース

より詳細な設定などはこちらを参照して下さい。

<https://github.com/pmarsceill/just-the-docs>

___

[remotetheme.github.io](https://remotetheme.github.io/)

