---
creation_date: <% tp.file.creation_date(string = "YY.MM.DD") %>
note_type: daily_note
aliases:
  - <% tp.date.now("YY년 MM월 DD일", 0, tp.file.title, "YY.MM.DD") %>
tags:
  - daily_note
PARA:
  - Archive
---

<< [[<% tp.date.now("YY.MM.DD", -1, tp.file.title, "YY.MM.DD") %>]] | [[<% tp.date.now("YY.MM.DD", 1, tp.file.title, "YY.MM.DD") %>]] >>

---
# Memo
1.  

## daily_cal
