---
marp: true
title: Learning With AI - Week 12
author: Preston Jackson
theme: default
paginate: true
---

# Learning with AI (As of Week 12)
### Preston Jackson

---

## Restating Goal for AI

- AI Book Recommendations
- AI Goal Creation Assist

---

### AI Book Recommendations

#### Reactive Machine AI
- Simplest form of AI

##### How it Works:
- Takes books from API database
- Takes books from Bookeep's stored books
- Compares books based off users books with a point value system
- Creates file and presents the top scoring books on BookHelp

---

### Demo

Link: https://youtu.be/ssGrE6MmKzg

---

### Recommendations Pros & Cons:

#### Pros:
- Makes good list
- Decent UI for Understandability, but was made by AI as a Placeholder
- Gives good Details on the book at just a glance

#### Cons:
- Uses Non-English Titles
- Favors most recent books too much
- Takes too long to load
- The "Hide" feature doesn't hide the book, rather just puts the book on a carousel

---

### Planned Changes
- Filter out non-English titles/version
- Reduce the points for recently read books
- Optimize code to reduce load times
- Replace AI's UI for better user experience (Make buttons more obvious, center buttons, etc.)

---
### Goal Setting Assists

- Not Currently In Development; Relies on BookStats

---

### Early Plan for Goal Setting

- Will take test history and time between books read
- Will generate a recommended goal based on that information
  - Will have 3 levels: Quick, Recommended, Optimistic
