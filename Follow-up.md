

```dataview
TASK WHERE !completed AND contains(tags, "#followup")
GROUP BY file.link
```
