---
type: daily
date: <% tp.date.now("YYYY-MM-DD") %>
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
tags:
  - daily
---

# <% tp.date.now("dddd, DD MMMM YYYY") %>

---
### Pending Tasks
```dataview
TASK
FROM ""
WHERE file.path = this.file.path
AND !completed
```

### Todo's

---

## 📅 Meetings

### Meeting: Meeting Name
- **Time:** HH:MM – HH:MM
- **Attendees:**
- **Agenda:**
  - 
- **Notes:**
  - 
- **Action Items:**
  - [ ] 

---

## 📝 Quick Notes
- 

---

## 📂 Notes Created Today

```dataview
LIST
FROM ""
WHERE file.cday = date("<% tp.date.now('YYYY-MM-DD') %>")
SORT file.ctime ASC
```