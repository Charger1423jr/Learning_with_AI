---
marp: true
title: Topic2
author: Preston Jackson
theme: default
paginate: true
---

# Learning with AI
## Topic 2: AI Goal Setting
### Preston Jackson

---

## What is it?
- AI Goal Recommendation System

---

## How does it Work?
- Uses Claude API
- User selects level they want to set their goals to (Quick, Recommended, Optimistic)
- Data gathered from user profile with metrics stored in BookStats
- Prompt will be sent to Claude API
- JSON Response sent back and parsed to be displayed on page for that user
- User chooses if this goal should be applied

---

## What Did I Learn?

1. First time setup is confusing
2. Finding good prompts to forward to Claude to get good feedback took time and trial+error
3. Translating the data back to the user display was surprisingly the easiest part
4. Claude API can make personal goals very well and gives good feedback on why this goal is perfect
