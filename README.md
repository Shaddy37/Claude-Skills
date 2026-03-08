# 🤖 Claude Skills

A collection of Claude Code skills for various use cases. These skills help automate workflows, boost productivity, and accelerate business growth.

---

## 📚 Available Skills

| Skill | Description | Usage |
|-------|-------------|-------|
| **linkedin-post-creator** | Create high-authority LinkedIn + X posts with images | `/linkedin [topic]` |
| **instagram-content-creator** | Instagram posts, carousels, Reels, Stories | `/instagram [topic]` |
| **linkedin-automation** | Automate LinkedIn tasks via MCP | Coming soon |
| **twitter-automation** | Automate Twitter/X tasks via MCP | Coming soon |
| **x-twitter-scraper** | X data platform skill for lead generation | Coming soon |

---

## 🚀 Quick Start

1. **Install skills to Claude Code:**
   ```bash
   Copy the skill folders to your `.claude/skills/` directory
   ```

2. **Use a skill:**
   ```
   /linkedin your-topic
   ```

---

## 📂 Repository Structure

```
Claude-Skills/
├── README.md
├── skills/
│   ├── linkedin-post-creator/
│   │   ├── SKILL.md              # Main skill definition
│   │   ├── templates/            # Post templates
│   │   ├── HOOKS_COLLECTION.md   # Proven hooks
│   │   └── ...
│   ├── instagram-content-creator/
│   │   ├── SKILL.md
│   │   ├── CAROUSEL_TEMPLATES.md
│   │   ├── REELS_IDEAS.md
│   │   └── ...
│   ├── linkedin-automation/
│   ├── twitter-automation/
│   └── x-twitter-scraper/
└── ...
```

---

## ➕ Adding New Skills

To add a new skill:

1. Create a folder in `skills/`
2. Add `SKILL.md` as the main skill file
3. Optionally add supporting files (templates, scripts, etc.)
4. Update this README

**Skill Structure:**
```
skills/
└── your-skill-name/
    ├── SKILL.md              # Required: Main skill definition
    ├── README.md             # Optional: Skill documentation
    ├── templates/            # Optional: Templates
    ├── scripts/              # Optional: Automation scripts
    └── ...
```

---

## 🔧 Requirements

- Claude Code CLI
- Node.js (for some skill scripts)

---

## 📝 Author

**Muhammad Shadab Shams**
- AI Automation Expert
- Helping Businesses Eliminate Manual Work with Automations

---

## 📄 License

MIT License - Feel free to use and modify.

---

*Built for AI Automation Experts*
