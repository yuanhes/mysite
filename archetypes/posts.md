---
title: {{ replace .File.ContentBaseName "-" " " | title }}
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
author: Yuanhe
# comments: false # display comments
# showToc: true
# TocOpen: true
# description: "" # article description, related to SEO
# summary: "" # article summary for showing on homepage
draft: true
tags:
  - default
categories: 
  - Life
---

