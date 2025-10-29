---
title: '"<% tp.file.title %>"'
publish_date: '"{{date:YYYY-MM-DD}}"'
"layout:": layouts.default.liquid
description: '""'
tags:
  - posts
---
<%*
let publishDate = tp.date.now("YYYY-MM-DD");
await tp.file.rename(publishDate + "-" + slug);
-%>

# <% tp.file.cursor(1) %>