If this helped you, consider starring the repo ⭐

---

# ✨ VibeCheck

<p align="center">
  <strong>A master checklist for vibecoding</strong><br>
  <em>Websites · Webapps · Windows apps · Scripts · Telegram bots · Android apps</em>
</p>

<p align="center">
  <code>🌐</code> <code>📱</code> <code>🖥️</code> <code>📜</code> <code>🤖</code> <code>📲</code>
</p>

One place to tick off everything before you ship. Glass-style UI, light/dark theme, drag-and-drop sections, and copy-paste AI prompts—so you can vibecode without missing a step.

---

## 📑 Table of contents

- [What is VibeCheck?](#-what-is-vibecheck)
- [Features](#-features)
- [Quick start](#-quick-start)
- [How to use](#-how-to-use)
- [GitHub Pages](#-github-pages)
- [Project structure](#-project-structure)
- [Tips](#-tips)
- [Attribution](#-attribution)

---

## 🎯 What is VibeCheck?

**VibeCheck** is a single-page checklist for projects you build with an AI-assisted, “vibecoding” workflow. It covers **13 phases** in order (naming, README, design, settings, logging, robustness, etc.) and **6 project types**:

| Section        | Emoji | What it covers |
|----------------|:-----:|----------------|
| **Websites**   | 🌐   | Static sites, landing pages, portfolios |
| **Webapps**    | 📱   | Web applications, dashboards, SPAs |
| **Windows apps** | 🖥️ | Desktop apps, CLI tools, launchers |
| **Scripts**    | 📜   | Automation, one-off scripts, pipelines |
| **Telegram bots** | 🤖 | Bots, commands, inline keyboards |
| **Android apps** | 📲 | Mobile apps, build, store, deep links |

Each section has **checkboxes** you tick as you go, **editable “Prompt to send to AI”** boxes you can copy and customize, and a **Clear** button per section. Your progress is saved in the browser (and in the file when you save).

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| ✅ **Checklists** | Tick off items per section; state is saved in the browser and in the file when you save. |
| 🎨 **Light / Dark theme** | Toggle in the header; preference is remembered. |
| ⋮⋮ **Drag & drop** | Reorder sections in the sidebar; cards and the “Section” dropdown update automatically. |
| 📂 **Open checklist** | Load a saved `.html` file and continue where you left off. |
| 💾 **Save checklist** | Download the current page as `VibeCheck.html` with all checks and edits. |
| ✏️ **Edit checklist** | Add new sections, add items to a section, delete items, clear checks. |
| 📋 **Editable prompts** | Change the “Prompt to send to AI” text and save it with the checklist. |
| 🧊 **Glass-style UI** | Frost/glass look with a simple, readable layout. |

---

## 🚀 Quick start

**Use it online (GitHub Pages)**  
→ Open your site (e.g. `https://YOUR_USERNAME.github.io/VibeCheck/`) and start ticking.

**Use it locally**  
→ Download or clone this repo, then open `VibeCheck.html` in your browser. No server needed.

**Save your progress**  
→ Use **Save checklist** to download the HTML. Use **Open checklist** later to load it back.

---

## 📖 How to use

### Sidebar

- **Open checklist** — Opens a file picker; choose a saved `VibeCheck.html` and the page reloads with that content.
- **Save checklist** — Downloads the current checklist as `VibeCheck.html` (or use the save dialog if the browser supports it).
- **Section list** — Click a section to scroll to it. **Drag the ⋮⋮ handle** (or the whole row) to reorder; the main cards and the “Section” dropdown update to match.

### Main area

- **Theme** — Use the **Light** / **Dark** dropdown in the header.
- **Checkboxes** — Tick items as you complete them. State is stored in the browser and in the file when you save.
- **Clear** — Each section card has a **Clear** button to uncheck all items in that section.
- **Delete** — Each checklist row has a **Delete** button to remove that item (and save).
- **Prompt to send to AI** — The text in each prompt box is **editable**. Edit it, then use **Save checklist** to keep your changes.

### Edit checklist bar

- **New section** — Enter a name, pick an emoji, click **Add section**. The new section appears in the sidebar and in the main grid and can be reordered.
- **Section** dropdown — Choose which section to add items to.
- **New item** — Type the item text and click **Add item** (or press Enter).

---

## 🌐 GitHub Pages

To host VibeCheck on GitHub Pages:

1. Push this repo to GitHub (or upload the files).
2. In the repo, go to **Settings** → **Pages** (left sidebar).
3. Under **Source**, choose **Deploy from a branch**.
4. **Branch:** e.g. `main`. **Folder:** **/ (root)**. Click **Save**.
5. Wait 1–2 minutes. Your site will be at:  
   **`https://YOUR_USERNAME.github.io/VibeCheck/`**  
   (use your GitHub username and repo name).

👉 **Detailed steps and troubleshooting:** [PAGES-SETUP.md](PAGES-SETUP.md)

---

## 📁 Project structure

```
VibeCheck/
├── index.html          → Redirects to VibeCheck.html (so the repo root opens the app)
├── VibeCheck.html      → The main checklist app (single file: HTML + CSS + JS)
├── README.md           → This file
├── PAGES-SETUP.md      → GitHub Pages setup guide
├── .nojekyll            → Tells GitHub Pages to serve files as-is
└── .gitignore
```

No build step. No dependencies to install. Just open the HTML or deploy the folder.

---

## 💡 Tips

- **Bookmark** your GitHub Pages URL or your local `VibeCheck.html` for quick access.
- **One file per project** — Save a copy as `MyWebsite-Checklist.html`, `MyBot-Checklist.html`, etc., and open the one you need.
- **Custom prompts** — Edit the “Prompt to send to AI” boxes for your stack and style, then save so they persist.
- **Reorder** — Put the sections you use most at the top by dragging them in the sidebar.

---

## 🙏 Attribution

**VibeCheck** · By [**AlexRabbit**](https://github.com/AlexRabbit)

If this helped you, consider starring the repo ⭐
