# 🧠 Objective

Mission: use AI tools to build a real landing page for your fictional startup.

⚡ Open your IDE (Cursor or similar)
🤖 Use AI agents (Cline, RooCode, etc.) to prompt and generate
🛠 Build, preview, tweak, regenerate
🔁 Iterate instead of debating
👥 Collaborate — one prompts, one reviews, one refines

Push the AI. Break things. Ask for improvements. Try bold prompts. This is about experimenting with AI-assisted building and seeing how far your team can go by prompting, iterating, and refining — fast.

# 👥 Team Structure (3–5 People)

Assign roles quickly (these are just a starting point—feel free to swap, combine, or invent new ones):

- **Prompt Architect** – Crafts and tweaks prompts for the AI
- **Builder** – Operates the IDE and implements changes
- **Product Lead** – Focuses the team on messaging and what makes your project useful
- **Designer (optional)** – Refines layout, colors, and overall looks

Tip: Rotate roles every round (round robin style), so everyone gets a turn prompting, building, and reviewing. This way, each team member can experience every part of the process, and ideas flow from all directions.


One laptop per team minimum.

# 🛠️ Tools Powering Your Build

---

HTML is the foundational structure of every website. It defines the content and layout of a page — things like headings, paragraphs, buttons, and sections. Think of it as the skeleton of a webpage: it organizes what appears on the screen, but not how it looks.

Tailwind is a CSS framework that controls how your HTML looks — spacing, colors, fonts, layout, and responsiveness. Instead of writing custom CSS, you use small utility classes directly in your HTML (like text-4xl, p-8, or bg-white) to style elements quickly. It makes building clean, modern designs much faster.

Cursor is an AI-powered code editor built on top of VS Code. It lets you generate, edit, and refactor code using built-in AI directly inside your project. Instead of switching between your editor and ChatGPT, Cursor acts like an AI teammate that can modify files, rewrite sections, and help you iterate faster.

# 🚀 Step-by-Step: Setting Up Cursor AI (First Time)

---

## 1️⃣ Download & Install Cursor

1. Go to: [https://cursor.sh](https://cursor.sh/)
2. Click **Download**
3. Install like a normal app (Mac / Windows)

It looks and feels like VS Code — because it’s built on it.

---

## 2️⃣ Sign In

When you open Cursor for the first time:

- It will prompt you to sign in
- Use Google or GitHub
- Free tier is enough for workshop use

You now have AI enabled by default.

No extra configuration required.

---

# 🧠 Understanding Cursor AI Modes

Cursor has 3 main AI workflows:

### 1. Chat (Project-Aware Agent)

Best for:

- “Build this landing page”
- “Refactor this file”
- “Add a section”

Shortcut:

- Open Chat panel (usually right sidebar)
- Or press `Cmd + L` (Mac) / `Ctrl + L` (Windows)

---

### 2. Inline Edit (Targeted Rewrite)

Best for:

- “Rewrite this paragraph”
- “Improve styling here”

How:

- Select code
- Press `Cmd + K`
- Type what you want changed

---

### 3. Full-Agent Editing

When you ask something like:

> Build a landing page in index.html
> 

Cursor will:

- Propose file edits
- Show diff preview
- Ask you to Accept changes

This is your “agent mode.”

---

# 🛠 Setup for Workshop (Clean & Simple)

---

## Step 1 — Create a Project Folder

Inside Cursor:

1. Click **File → Open Folder**
2. Create new folder: `startup-landing`
3. Open it

---

## Step 2 — Create index.html

In left sidebar:

- Click “New File”
- Name it: `index.html`

---

## Step 3 — Add Tailwind CDN Starter

Paste this minimal starter:

```
<!doctype html>
<html>
<head>
<metacharset="UTF-8">
<metaname="viewport"content="width=device-width, initial-scale=1.0">
<title>Startup</title>
<scriptsrc="https://cdn.tailwindcss.com"></script>
</head>
<bodyclass="bg-white text-slate-900">
<h1class="text-4xl font-bold p-8">Hello World</h1>
</body>
</html>
```

Save.

---

# 🤖 Now: Use Cursor AI Agent

Open Chat panel.

Paste this:

```
We are building a landing page in index.html using Tailwind via CDN.

Startup name: [NAME]
Context:
[PASTE CONTEXT]

Build:
- Hero section
- Features section
- Testimonials
- Pricing
- FAQ
- Footer

Keep it in one single HTML file.
Make it clean, modern, and responsive.
Only edit index.html.
```

Cursor will:

1. Think
2. Show file changes (diff view)
3. Ask you to accept

Click **Accept All/Accept file**

You now have a full landing page.

---

# 🖥 Previewing in Cursor

Simplest options:

### Option A — Open File in Browser

Right click `index.html` → Reveal in Finder

Double click file to open in browser.

Refresh after edits.

---

### Option B — Install “Live Server” Extension (Recommended)

1. Open Extensions panel
2. Search: **Live Server**
3. Install
4. Click “Go Live”

Now it auto-refreshes.

---

# 🔄 How to Iterate Like a Pro

After version 1:

### Improve Design

```
Improve the visual design to feel more modern and startup-like.
Better spacing, typography hierarchy, and subtle hover effects.
Keep it clean and minimal.
```

### Improve Copy

```
Rewrite the copy to be more specific and human.
Avoid buzzwords.
Make the value proposition clear.
```

### Change Vibe

```
Restyle the page in a bold neon tech aesthetic.
Keep structure same, update Tailwind classes only.
```

---

# 🧠 Important Settings (Optional but Helpful)

Go to:

Cursor → Settings

Enable:

- “Auto Apply simple edits”
- “Show diff before apply” (recommended for safety)

You don’t need to configure any API keys.

Cursor handles model access in the free tier.

---

# 👥 How Teams Should Use Cursor

Recommended pattern:

- Person A: Drives editor
- Person B: Writes prompt
- Person C: Reviews result
- Everyone reacts quickly

Rule:

If stuck → prompt.

If messy → regenerate.

If debating → ship v1 first.

---

# 🧪 If Cursor AI Stops Responding (Free Tier Limit)

Have a backup:

- Open ChatGPT or any other similar AI Chat app (Gemini, CoPilot, etc) you have access to in browser
- Generate full HTML
- Paste into Cursor

Zero drama.