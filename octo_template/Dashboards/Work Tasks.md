---
tags:
  - work
  - tasks
  - todo
---
# Tasks

## Due Today
>[!check]+ Due today
> ```tasks
> (path includes Work) OR (tag includes #work) OR (tag includes #sunward)
> not done
> due on today
> sort by description
> ```

## Due Soon
>[!check]+ Due soon
> ```tasks
> (path includes Work) OR (tag includes #work) OR (tag includes #sunward)
> not done
> due after today
> (due in this week) OR (due in next week)
> sort by description
> ```

## Overdue
> [!danger]+ Overdue  
> ```tasks  
> not done  
> ((path includes Work) OR (tag includes #work) OR (tag includes #sunward))
> due before today
> hide recurrence rule  
> sort by due date  
> ```

## Backlog
> [!todo]- Backlog
> ```tasks
> not done
> ((due after today) OR (no due date))
> (path includes Work) OR (tag includes #work) OR (tag includes #sunward)
> path does not include templates
> sort by due
> sort by description
> ```


---

# Information
Further information and guides can be found in the [[obsidian]] note.