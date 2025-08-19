---
title: {{ replace .File.ContentBaseName "-" " " | title }}
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
author: Yuanhe
draft: true
tags:
  - default
categories: 
  - Life
---

