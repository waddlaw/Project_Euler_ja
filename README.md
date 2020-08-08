# [Project Euler][project_euler] 和訳

## ライセンス

**CC BY-NC-SA 4.0**です。

2020-7-29 GitBookからOpenSource活動として承認されました！

[https://project-euler-ja.gitbook.io/project-euler-ja/][gitbook], [https://github.com/gotoki-no-joe/Project\_Euler\_ja][github] で公開しながらコツコツ[webarchive][webarchive]からサルベージ中です。

[project_euler]: https://projecteuler.net/
[gitbook]: https://project-euler-ja.gitbook.io/project-euler-ja/
[github]: https://github.com/gotoki-no-joe/Project_Euler_ja
[webarchive]: https://web.archive.org/web/20161030010432/http://odz.sakura.ne.jp/projecteuler/index.php?Project%20Euler

## メモ

* digit と number の訳し分けが出来ていないところがある。
* パンデジタル、などの用語の説明をまとめて書くとよいかも。
* 締めの言葉を統一したい。
* オリジナルへのリンクを忘れた。
* 何らかの問題が残っているページのタイトルには\(\*\)が付けてある。

## コントリビュート

PR welcome :)

* GitBook v2 の使い方については[GitBook の公式ドキュメント][gitbook-doc]を参照
* インラインの数式は `$$...$$` というように囲む必要があるので注意
* VSCODE などのエディタ内で GitBook の数式をプレビューしたい場合は [Markdown Preview Enhanced][preview-md] がオススメ。`settings.json` に以下の内容を追記すると良い感じに表示されます。

```json
  "markdown-preview-enhanced.mathInlineDelimiters": [
    [
      "$$",
      "$$"
    ]
  ],
  "markdown-preview-enhanced.mathBlockDelimiters": [
    [
      "$$\n",
      "$$"
    ]
  ],
```

[gitbook-doc]: https://docs.gitbook.com/
[preview-md]: https://github.com/shd101wyy/vscode-markdown-preview-enhanced