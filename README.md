# 💬 LeetCode Gemini Chat Assistant Extension

A Chrome Extension that adds an AI-powered chat assistant to [LeetCode](https://leetcode.com/problems/*) to help you understand and solve coding problems using Google Gemini API.

Built with **React + TypeScript + TailwindCSS + Vite + Manifest V3**.

---

## ✨ Features

- 💬 Floating "Chat with Gemini" button on LeetCode problem pages
- 📄 Automatically extracts problem title and description
- 🤖 Sends problem data + your queries to Gemini API (Pro)
- 🧠 Chat UI with Markdown + syntax highlighting + code copy
- 🔐 Stores Gemini API key securely via `chrome.storage.local`
- ⚙️ Options page to save/update/remove your API key

---

## 📦 Tech Stack

- **Frontend**: React + TypeScript + TailwindCSS
- **Bundler**: Vite
- **Chrome API**: Manifest V3, `chrome.storage`, `chrome.scripting`
- **AI**: Google Generative AI (Gemini Pro API)

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/Vikaslh/leetcode-helper.git
cd leetcode-helper
npm install


###2 . Set up Tailwind (if not yet)
npx tailwindcss init -p
Edit tailwind.config.js:

content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"]
Add to src/index.css:

@tailwind base;
@tailwind components;
@tailwind utilities;


3. Build the Extension
npm run build


4. Load into Chrome
Open chrome://extensions
Enable Developer mode
Click "Load unpacked"
Select the dist/ folder
🛠️ Usage

Go to chrome://extensions → click Details → open Options
Paste your Gemini API key
Visit any LeetCode problem
Click 💬 Chat with Gemini
Ask questions like:
"Explain this problem"
"Give me a Python solution"
"Optimize the code"
"Explain with example"
