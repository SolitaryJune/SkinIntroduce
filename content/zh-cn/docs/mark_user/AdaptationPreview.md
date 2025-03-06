---
title : "三、适配预览 皮肤|图标等文件"
description: "作者 ｜ 孤傲"
lead: "作者 ｜ 孤傲"
date: 2021-08-19T08:49:31+00:00
lastmod: 2021-08-19T08:49:31+00:00
draft: false 
images: []
menu:
  docs:
    parent: "mark_user"
toc: true
weight: 30
---

### 适配预览 皮肤|图标等文件说明

使用关键词**加密凭证 | 普通加密凭证**，bdi | bds | it 文件默认会读取预览图。部分 skini | skinb 文件可能读取不到原生预览图，建议适配。

## 皮肤|图标等文件 预览图适配

适配**文件结构**如下

- bdi | bds | it | skini | skinb /
  - GuShao.png  （预览图）
  - demo.png
  - 文件夹2 （皮肤的dark，light或res）
  - 文件3.png （图标）

总之，文件打开第一层必须要有GuShao.png才能使用预览图功能。

注：皮肤文件如无GuShao.png，将会自动读取demo.png作为预览图。图标文件如无demo.png/GuShao.png，则不显示预览图。
