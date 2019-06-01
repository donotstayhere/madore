---
title: Madore
author: 
- name: サンプル\ 名前
  id-number: 12345678
- name: ジョン\ ワトソン
  id-number: 87654321
papersize: a4
documentclass: bxjsreport
classoption:
- pandoc
- jafont=ipaex
fontsize: 11pt
linkcolor: black
listings: true
codeBlockCaptions: true
---

# タイトル
[@lst:code]に示す

```{#lst:code .python caption="Listing caption"}
for i in range(10):
  print('hello')
```