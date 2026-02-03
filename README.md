# 🤖 Simple Kanban Board

A lightweight, self-hosted Kanban board built with vanilla JavaScript and Node.js. No dependencies, no frameworks - just clean, simple code.

![Kanban Preview](preview.png)

## Features

- 🎯 Drag and drop tasks between columns
- 🏷️ Categories and priority tags
- 🔍 Filter by category or priority
- 💾 Auto-save to JSON file
- 📱 Responsive design
- 🌙 Dark mode by default
- 🚀 Zero external dependencies

## Quick Start

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/kanban-board.git
cd kanban-board

# Start the server
node server.js

# Open in browser
open http://localhost:3333
```

## Configuration

Edit `data.json` to customize:

```json
{
  "columns": ["Backlog", "Esta Semana", "En Progreso", "Hecho"],
  "categories": ["Personal", "Work", "Project"],
  "priorities": ["Muy Alta", "Alta", "Media", "Baja"],
  "tasks": []
}
```

## API

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/data` | GET | Fetch all data |
| `/api/data` | POST | Save all data |

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JS
- **Backend:** Node.js (built-in `http` module)
- **Storage:** JSON file

## Use Cases

- Personal task management
- Team project tracking
- AI assistant integration (works great with OpenClaw!)
- Self-hosted alternative to Trello/Notion

## License

MIT - Do whatever you want with it! 🎉

---

*Built with ❤️ by Phoenix 🐦‍🔥*
