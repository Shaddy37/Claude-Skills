# 📅 CALENDAR_FORMAT.md
## Content Calendar Structure for LinkedIn + X

---

## 🎯 Overview

This guide explains the calendar structure for scheduling posts. Later, this will integrate with ClickUp for easy copy-paste scheduling.

---

## 📊 Calendar Structure

### CSV Format

| Field | Description | Example |
|-------|-------------|---------|
| date | Post date | 2026-03-09 |
| time | Post time | 09:00 |
| platform | linkedin or x | linkedin |
| post_type | Type of post | carousel |
| topic | Topic/focus | AI Automation |
| hook | Hook to use | results-focused |
| status | draft/scheduled/posted | draft |
| content_file | Path to content | post-001.txt |
| image_file | Path to image | image-linkedin.png |
| notes | Additional notes | Use CTA: automate |

---

## 📆 Daily Format

### LinkedIn (AM - 9:00 AM)
```
| date | time | platform | post_type | topic | hook | status |
|------|------|----------|-----------|-------|------|--------|
| 2026-03-09 | 09:00 | linkedin | carousel | AI Automation | results | draft |
```

### X (PM - 5:00 PM)
```
| date | time | platform | post_type | topic | hook | status |
|------|------|----------|-----------|-------|------|--------|
| 2026-03-09 | 17:00 | x | thread | AI Automation | results | draft |
```

---

## 📋 Weekly Template

### Week of March 9-15, 2026

| Day | LinkedIn | X |
|-----|----------|---|
| Mon | Carousel | Thread |
| Tue | Case Study | Single |
| Wed | Tool Stack | Thread |
| Thu | Opinion | Quote |
| Fri | Question | Engagement |
| Sat | Story | Single |
| Sun | Recap | Thread |

---

## 🔗 ClickUp Integration

### When Importing to ClickUp

1. Export calendar as CSV
2. Import into ClickUp
3. Map fields to tasks:
   - Date → Due Date
   - Time → Time Tracker
   - Platform → Tag
   - Topic → Custom Field
   - Status → Task Status

### ClickUp Task Template

```
Task Name: [TOPIC] - [PLATFORM]
Due Date: [DATE]
Time: [TIME]
Description: [POST TYPE] - [HOOK]
Tags: [PLATFORM], [POST_TYPE]
```

---

## 📝 Example Calendar Entry

### LinkedIn Post

```
date: 2026-03-09
time: 09:00
platform: linkedin
post_type: carousel
topic: 5 Steps to Automate Process
hook: results-focused
status: draft
content_file: 2026/03/post-001-carousel-steps.txt
image_file: 2026/03/images/post-001-linkedin.png
cta: Save for later
notes: First carousel post - test format
```

### X Thread

```
date: 2026-03-09
time: 17:00
platform: x
post_type: thread
topic: 5 Steps to Automate Process
hook: results-focused
status: draft
content_file: 2026/03/post-001-thread-steps.txt
image_file: 2026/03/images/post-001-x.png
cta: Follow for more
notes: Thread version of carousel
```

---

## ✅ Calendar Best Practices

1. **Plan ahead**: Schedule 1 week at a time
2. **Batch content**: Create multiple posts in one session
3. **Leave flexibility**: Mark some as "draft" until ready
4. **Track performance**: Add metrics after posting
5. **Review weekly**: Adjust based on results

---

## 📊 Metrics to Track

| Field | Track |
|-------|-------|
| impressions | After posting |
| engagement | After 24 hours |
| comments | After 24 hours |
| saves | After 24 hours |
| shares | After 24 hours |
| leads_generated | After 1 week |
| revenue_attributed | After 1 month |

---

*See export_template.csv for ready-to-import format*
