# madore

Pandoc Markdown to PDF report template

## 概要

Pandocを使ってMarkdownでレポートを作るときのテンプレートです。
日本語でのレポート向けです。

日本語フォントをサポートしてるので日本語をそのまま書くことができます。

## 使い方

Markdownを用いて書きます。sample.md を編集して使ってください。(ファイル名は適当なものに変更できます。)

### 環境

- [Pandoc](https://pandoc.org/)
- [Pandoc Crossref](https://lierdakil.github.io/pandoc-crossref/)
- [MiKTeX](https://miktex.org/)

### PDFにするには？

MarkdownをPDFにするにはコンソールで

```
pandoc sample.md -o sample.pdf --pdf-engine=xelatex -s -N -F pandoc-crossref --template madore --listings
```

を実行してください。

Windowsの場合はmdtopdf.batを実行するとPDFが生成されます。