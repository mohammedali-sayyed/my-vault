
---
type: weekly
date: <% tp.date.now("YYYY-MM-DD") %>
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
week: <% tp.date.now("gggg-[W]WW") %>
week_start: <% tp.date.weekday("YYYY-MM-DD", 0) %>
tags:
  - daily
---

# <% tp.date.now("YYYY-[W]WW") %>

---
### Pending Tasks
```dataview
TASK
FROM "journal/daily"
WHERE !completed
  AND file.day >= date(this.week_start)
  AND file.day < date(this.week_start) + dur(7 days)
GROUP BY file.link
```

