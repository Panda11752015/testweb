# 🗓️ DayFlow — AI-Powered Daily Planner

A gorgeous, single-file daily schedule planner powered by Claude AI. Drop it on GitHub Pages and use it instantly from any browser.

![DayFlow Screenshot](https://via.placeholder.com/800x400/0d0f14/7c6af7?text=DayFlow+AI+Daily+Planner)

## ✨ Features

- **AI Time-Blocking** — Paste your to-do list, Claude builds a full color-coded schedule
- **Action Plans** — Every task gets prep steps, action items, tips, and alternatives
- **Google Calendar Export** — One click opens each block directly in Google Calendar
- **Daily Note Export** — Markdown note ready for Notion, Obsidian, or any note app
- **Retry Any Block** — Re-generate just one task's plan with custom instructions
- **Customizable Prompt** — Edit the Claude system prompt directly in the UI
- **Day Progress Bar** — See how far through your day you are in real-time
- **Drag-to-Reorder** — Reorder tasks before generating

## 🚀 Deploy to GitHub Pages (2 minutes)

1. Fork or create a new repo
2. Upload `index.html` to the root
3. Go to **Settings → Pages → Source: main branch / root**
4. Visit `https://yourusername.github.io/your-repo-name`

That's it. No build step, no dependencies, no server.

## 🔑 API Key

You need a Claude API key from [console.anthropic.com](https://console.anthropic.com).

Enter it in the sidebar. It stays in your browser session only — never stored, never sent anywhere except Anthropic's API.

## 🛠 Customizing the Prompt

Click **⚙️ Prompt** in the top bar to edit the system prompt sent to Claude. Available placeholders:

| Placeholder | Description |
|---|---|
| `{tasks}` | Comma-separated task list |
| `{date}` | Today's date string |
| `{startTime}` | Day start time |
| `{endTime}` | Day end time |

## 📁 File Structure

```
index.html    ← The entire app (HTML + CSS + JS, one file)
README.md     ← This file
```

## 🎨 Color Categories

| Color | Category |
|---|---|
| 🟣 Purple | Deep Work |
| 🔴 Pink/Red | Meetings |
| 🟢 Teal | Breaks |
| 🟡 Yellow | Admin |
| 🔵 Blue | Learning |
| 🔷 Violet | Exercise |
| 🟠 Orange | Personal |
| 💚 Green | Planning |

## 📅 Google Calendar Export

Clicking **Add to Google Calendar** opens each time block as a separate Google Calendar event with:
- Task title and time
- Description with action plan
- Tips embedded in the event notes

## 📝 Daily Note Export

Exports a full Markdown document including:
- Day title & stats
- All time blocks with checkboxes
- Action plans in checklist format
- Blank sections for notes, wins, and tomorrow's focus

Ready to paste into **Notion**, **Obsidian**, **Roam**, **Logseq**, or any Markdown editor.

## 🧩 Tech Stack

- Vanilla HTML/CSS/JS (zero dependencies)
- [Claude API](https://docs.anthropic.com) — `claude-haiku-4-5`
- Google Fonts: Syne + DM Sans + DM Mono
- Fully client-side — works as a static file

## License

MIT — free to use, modify, and share.
