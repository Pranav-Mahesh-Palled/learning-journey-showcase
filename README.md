# Learning Journey Showcase Workflow

## Overview

This workflow converts learning notes stored in Google Sheets into polished social media posts for LinkedIn and X/Twitter. It helps showcase daily progress, skills learned, and technical growth in a more engaging way.

---

## Problem Statement

Students often learn a lot every day, but they do not always know how to turn that progress into public content.

Writing separate posts for LinkedIn and X manually takes time and consistency is difficult to maintain.

---

## Solution

The workflow:
1. Watches a Google Sheet for new learning entries.
2. Summarizes the learning into a short professional explanation.
3. Generates a LinkedIn post.
4. Generates an X/Twitter post.
5. Publishes both posts using the connected accounts.

---

## Workflow Architecture

Google Sheets Trigger  
↓  
Learning Summary Generation  
↓  
LinkedIn Post Generator  
↓  
X/Twitter Post Generator  
↓  
LinkedIn Publish  
↓  
X Publish

---

## Technologies Used

- n8n
- Google Sheets
- Google Gemini
- LinkedIn API
- X/Twitter API

---

## How It Works

### Step 1: Learning Data Entry
A new row is added in Google Sheets containing:
- date
- topic/module
- what was learned
- tools used

### Step 2: Summary Generation
The workflow turns the raw learning note into a short achievement summary.

### Step 3: Social Post Generation
The summary is expanded into:
- a LinkedIn post
- a short X post

### Step 4: Publishing
The posts are published on each platform.

---

## Input Columns

- Date
- Topic/Module
- What I Learned
- Skills/Tools

---

## Output

- a polished LinkedIn post
- a short X post
- public learning visibility
- consistent content output

---

## Setup Instructions

1. Import the workflow JSON into n8n.
2. Connect Google Sheets credentials.
3. Connect Gemini credentials.
4. Connect LinkedIn and X credentials.
5. Add rows in the learning sheet.
6. Test the workflow.

---

## Future Improvements

- Add a content approval step
- Add hashtag optimization
- Add carousel post generation
- Add weekly summary posts

---

## Author

Pranav Mahesh Palled
