---
tags: ['reading', 'books', 'writing', 'notes']
title: "{{title}}"
author: [{{author}}]
publisher: {{publisher}}
publish: {{publishDate}}
total_page: {{totalPage}}
isbn: {{isbn10}} {{isbn13}}
cover_url: {{coverUrl}}
status: unread
created: {{DATE:YYYY-MM-DD HH:mm:ss}}
updated: {{DATE:YYYY-MM-DD HH:mm:ss}}
---
[TOC]

---

# {{title}}

![cover|150]({{coverUrl}})

| Title    | **`$=dv.current().title`**    | 
| -------- | ----------------------------- |
| Author   | `$=dv.current().author`       |
| Category | `$=dv.current().category`     |
| Pages    | `$=dv.current().total_page`   |
| Year     | `$=dv.current().publish_date` |

## Chapter Notes

### Chapter 1

