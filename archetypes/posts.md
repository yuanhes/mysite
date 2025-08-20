---
title: {{ replace .File.ContentBaseName "-" " " | title }}
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
author: Yuanhe
#showToc: true
#TocOpen: true
#description: "" # related to SEO
summary: "" # summary for homepage display
draft: true
tags: ["default"]
categories: ["Life"] # Life, Tech, Science, Art, Thoughts
---

