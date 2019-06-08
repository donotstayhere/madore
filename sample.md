---
title: Madore
author: 
- name: sample\ name
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

# Title

## Title

### タイトル

# Code

[@lst:code] is a sample code

```{#lst:code .python caption="Listing caption"}
for i in range(10):
  print('hello')
```