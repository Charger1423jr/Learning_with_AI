---
marp: true
title: Learning With AI
author: Preston Jackson
theme: default
paginate: true
---

# Learning with AI
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

### What I Learned from This
- AI can do really well making simple recommendations
- However, model has high recency bias (Author of most recent book favored)
- AI translates books for itself and recommends non-English books. Had to manual filter them out from API.

---

### Goal Setting Assists

- Takes test outcomes stored in data (Time between books logged, test history)
- Generates a "Recommended Goal" for WPM goal and Comprehension Goal + Streak Expectations
- User chooses if AI should set a quick goal, recommended goal, or an optimistic goal

---

### What I Learned from This

- AI goals were extremely optimistic, even with quick goals at first. Had to tweak.
- Then, AI was tip-toeing up for goals (Made goals increase by 1 WPM for quick... technically works, but can be better)
- Overall, it fought me every step of the way

---

### Writing to AI

- Claude's token limit is stupid
- I started off this project still not giving AI enough information, so it guesses so much for development. Much AI troubleshooting early on.
- Now, my prompts (or AIs reading capabilities) have grown; Notice that AI feedback or code snippets are much better and accurate to my design
