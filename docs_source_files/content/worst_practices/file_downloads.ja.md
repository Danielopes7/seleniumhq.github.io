---
title: "ファイルダウンロード"
weight: 2
---


Seleniumの管理下にあるブラウザーでリンクをクリックしてダウンロードを開始することは可能ですが、APIはダウンロードの進行状況を公開しないため、ダウンロードしたファイルのテストには理想的ではありません。
これは、ファイルのダウンロードは、Webプラットフォームとのユーザーインタラクションをエミュレートする重要な側面とは見なされないためです。
代わりに、Selenium（および必要なCookie）を使用してリンクを見つけ、 [libcurl](//curl.haxx.se/libcurl/) などのHTTPリクエストライブラリに渡します。