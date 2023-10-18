---
tags: DailyNotes
created: 2023-10-16 08:37
banner: "/assets/banner/Forest_Steph_Johnstone.jpg"
---

# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

⬅️ [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').subtract(1, 'd').format('YYYY-MM-DD-dddd') %>|Gestern]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').add(1, 'd').format('YYYY-MM-DD-dddd') %>|Morgen]] ➡️

---

# 📝 Notes

## 🎒Uni

---

# 📅 Kalender

---

> [!SUMMARY] 😎 Erstellte Notizen
>
> ```dataview
> List FROM "" WHERE file.cday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.ctime asc
> ```

> [!SUMMARY] ✒️ Bearbeitete Notizen
>
> ```dataview
> List FROM "" WHERE file.mday = date("<%tp.date.now("YYYY-MM-DD")%>") SORT file.mtime asc
> ```