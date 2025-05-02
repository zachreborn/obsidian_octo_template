---
tags:
  - tasks
  - todo
  - dashboard
  - shopping
---
# Tasks

## Due Today
>[!check]+ Due today
> ```tasks
> path does not include Work
> tag does not include #work
> tag does not include #sunward
> not done
> due on today
> sort by description
> ```

## Due Soon
>[!check]+ Due soon
> ```tasks
> path does not include Work
> tag does not include #work
> tag does not include #sunward
> not done
> due after today
> (due in this week) OR (due next week)
> sort by description
> ```

## Overdue
> [!danger]+ Overdue  
> ```tasks  
> not done  
> path does not include Work
> tag does not include #work
> tag does not include #sunward
> due before today
> hide recurrence rule  
> sort by due date  
> ```

## Backlog
> [!todo]- Backlog
> ```tasks
> not done
> ((due after today) OR (no due date))
> path does not include templates
> path does not include Work
> tags does not include #purchase
> tags does not include #shopping
> tags does not include #work
> tags does not include #sunward
> sort by due
> sort by description
> ```

---

# Shopping List
> [!example]+ Shopping List  
> ```tasks  
> not done  
> ((tag includes #purchase) OR (tag includes #shopping))
> hide recurrence rule  
> sort by due date 
> sort by description
> ```

---

# Information
Further information and guides can be found in the [[obsidian]] note.