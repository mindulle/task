# {{title}}
## Tasks due today

## Log
- [x] This is a task from daily note. [[yyyy-mm-dd]]
```dataviewjs
dv.taskList(dv.pages().file.tasks
  .where(t => !t.completed)
  .where(t => t.text.includes("yyyy-mm-dd")))
```