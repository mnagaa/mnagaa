---
title: "Github Pages + Hugo"
date: 2022-08-07T16:31:51+09:00
draft: false
---


Github PagesとHugoでProfileページを作って公開する。



## 更新方法


`hugo new post/${pageTitle}.md`で新しいページを作成する。
そして、マークダウンファイルを更新する。
公開したい場合は`draft: false`に変更する。


`config.yml`のbaseURLのしたあたりに、`publishDir: "docs"`を追加する。

`hugo`でビルドが開始され、docsの配下に公開用のファイルが生成される。
