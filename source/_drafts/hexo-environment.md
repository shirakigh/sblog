---
title: hexo-environment
tags:
---
下記は自分の覚書も兼ねた技術メモです。
興味のある方はどうぞ。

<!-- more -->

### HEXO環境

#### プラグインとか

現在の環境はこんな感じです。

```
+-- hexo@3.2.2
+-- hexo-deployer-git@0.2.0
+-- hexo-generator-archive@0.1.4
+-- hexo-generator-category@0.1.3
+-- hexo-generator-feed@1.2.0
+-- hexo-generator-index@0.2.0
+-- hexo-generator-search@1.0.2
+-- hexo-generator-sitemap@1.1.2
+-- hexo-generator-tag@0.2.0
+-- hexo-renderer-ejs@0.2.0
+-- hexo-renderer-jade@0.2.0
+-- hexo-renderer-marked@0.2.11
+-- hexo-renderer-stylus@0.3.1
+-- hexo-server@0.2.0
`-- hexo-tag-bootstrap@0.0.8
```

jadeはテーマの中で必要なものがあったのでインストールしました。

#### テーマ

テーマは色々試したんですが、最終的に公式のテーマ集に掲載されているBootstrap-blogをベースに色々とカスタマイズしました。

> hexo-theme-bootstrap-blog
> https://github.com/cgmartin/hexo-theme-bootstrap-blog

メニューのカテゴリ一覧やタグ一覧、ウィジェットのタグクラウドの表示などはFreemindを参考にしました。

> hexo-theme-freemind
> https://github.com/wzpan/hexo-theme-freemind

テーマと記事を完全に分離して編集できるのはすごく便利ですね。
テーマの切り替えも `_config.yml` の書き換えだけで済むし。

### Atom

エディタとファイル管理はAtomを使ってます。
もともと、仕事でAngularJS開発→Atom使う→Markdown知る→HEXO知る、という流れだったので、せっかくならAtom使ってブログ書きたいなと思っていたんですよね。

#### プラグイン

Atomで使ってるプラグインは下記のとおりです。

Markdown系：
+ language-markdown
+ markdown-writer
+ markdown-previre-enhanced
