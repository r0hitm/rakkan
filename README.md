# Rakkan

![Project Status](https://img.shields.io/badge/status-prototyping-yellowgreen)
![Development Stage](https://img.shields.io/badge/development-early%20dev-orange)

Simple offline-first tasks app using todo.txt philosophy.

## Motivation
I want a todoist alternative that's **offline-first**, and simple. Nothing in the market exists at the moment, so I am gonna write one for my personal use. I found [todo.txt](https://github.com/r0hitm/todo.txt?tab=readme-ov-file) and want to try it but I do not want to manually keep track of its 3 basic rules and syntax. I will use this project as a prototyping work-horse to develop my flavor of todo.txt that's offline first and minimal.

## Rakkan - One thing at a time, start now
Rakkan (first one), Rakan(second)
- **楽観**【らっかん】 — _Optimism / positive outlook_
    - Fits a mindful, light productivity system
    - Almost ironic minimalism: calm interface, clear goals
- **羅漢**【らかん】 — _Arhat / disciplined monk_
    - A person who has attained enlightenment through self-discipline
    - Stoic, powerful — fits a minimalist app with no fluff, only purpose

### Rules/Syntax - my preference

```
[x] ![priority] [task] +[project tag] @[context tag] due:[date]
```

- x means the task is complete (approach 1), or cut-paste the task into a done.txt (approach 2), delete the task (approach 3).
- priority is a number from 1 (highest priority) to 4 (backburner)
- project tag is for managing bigger tasks by breaking them up into smaller (fleeting because I am creating deleting them as per projects, NOT areas/categories - this is something new to me because of todoist's project structure). Plus a task have more than 1 projects associated w/ it.
- context is basically tags, as per GTD split into place, time or other cues e.g household stuff in @home, messages in @email etc
- due:*date* must be a ISO YYYY-MM-DD
- additional metadata can be defined as key:value

#### INVARIANTS/RULES:
1. If priority exists, it ALWAYS appears first.
2. Contexts and Projects may appear anywhere in the line after priority/prepended date.
