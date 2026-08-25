---
title: typora破解
published: 2026-08-26
description: 'typora破解，支持1.9.5之前'
tags: [typora]
category: 破解软件
draft: false 
---

# 1.下载typora1.9.5版

[Windows 64位版](https://downloads.typora.io/windows/typora-setup-x64-1.9.5.exe)

# 2.修改文件

打开安装目录

```
\resources\page-dist\static\js\LicenseIndex.180dd4c7.4da8909c.chunk.js
```

将

```
hasActivated="true"==e.hasActivated
```

改为

```
hasActivated="true"=="true"
```
