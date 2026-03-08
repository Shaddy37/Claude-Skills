# AGENTS.md - AI Automation Workspace

This workspace is for **AI-powered content creation and marketing automation** - not a traditional software project. It contains Claude Code skills, content outputs, and workflow tools.

---

## 📁 Workspace Structure

```
E:\Antigravity\Shadab\
├── .claude/skills/          # Claude Code skills (main "code")
│   ├── linkedin-post-creator/  # LinkedIn + X content generation
│   ├── instagram-content-creator/
│   └── ...
├── Claude-Skills/            # GitHub repo for skill distribution
├── linkedin-posts/           # Generated LinkedIn content
├── instagram-posts/          # Generated Instagram content
├── notion-toolkit/           # Notion automation tools
└── .mcp.json               # MCP server configurations
```

---

## 🎯 Available Skills

| Command | Description |
|---------|-------------|
| `/linkedin [topic]` | Create LinkedIn + X posts with images |
| `/instagram [topic]` | Create Instagram posts, carousels, Reels |
| `/crawl [url]` | Crawl websites to markdown |
| `/extract [url]` | Extract content from URLs |
| `/research [topic]` | Web research with citations |
| `/search [query]` | Tavily web search |

---

## ⚙️ MCP Configuration

- **Notion MCP**: Enabled via `npx mcp-remote` in `.mcp.json`
- Token: Already configured (do not expose)

---

## 📝 Content Creation Workflow

### LinkedIn Posts (2x/day)
1. Use `/linkedin [topic]` command
2. Skill creates BOTH LinkedIn AND X posts automatically
3. Generates image prompts for Canva-style visuals
4. Posts saved to `linkedin-posts/2026/Month/`

### Instagram Posts
1. Use `/instagram [topic]` command
2. Select format: Carousel, Reel, Single, or Story
3. Generates image prompts with PURPLE theme
4. Posts saved to `instagram-posts/`

---

## 🎨 Brand Guidelines

- **Primary Color**: PURPLE (#7B2CBF, #9D4EDD)
- **Name**: Muhammad Shadab Shams
- **Signature**: SHADAB SHAMS | AI Automation Expert
- **Style**: Clean, Canva-style minimalist (NO shiny AI effects)

---

## 📂 GitHub Repository

**Repo**: https://github.com/Shaddy37/Claude-Skills

To push updates:
```bash
cd Claude-Skills
git add -A
git commit -m "description"
git push
```

---

## 🔧 Running Skills

Skills are invoked via Claude Code commands:
- Start with `/` to activate a skill
- Or describe your intent naturally

---

## ⚠️ Security Rules

- Never expose API keys or tokens in code
- MCP tokens are in `.mcp.json` - do not share
- Personal data (emails, phones) should not be committed
- Run security checks before pushing to GitHub

---

## 📋 Content Calendar

- **LinkedIn**: 2x/day (morning + afternoon)
- **Instagram**: Based on CONTENT_CALENDAR.md in skills

---

## 🔄 Syncing Skills from GitHub

To update local skills from GitHub:
```bash
# Clone or pull latest
git clone https://github.com/Shaddy37/Claude-Skills.git
# Or
cd Claude-Skills && git pull

# Copy updated skills to local
cp -r Claude-Skills/skills/* .claude/skills/
```

---

*Last Updated: 2026-03-09*
