<div align="center">

# 🎬 Editkaro.in — Video Editing Portfolio

**A bold, single-page portfolio concept for a social-first video editing and post-production agency.**

*Gaming • Advertising • Anime • Short-form content — showcased in a dark, vibrant layout.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Build](https://img.shields.io/badge/Build_Step-None-brightgreen?style=for-the-badge)

[Preview](#-preview) •
[Features](#-features) •
[Getting Started](#-getting-started) •
[Structure](#-project-structure) •
[Customization](#-customization) •
[Notes](#-notes)

</div>

---

> [!TIP]
> **No build step required.** Just open the HTML file in your browser and start exploring. 🚀

---

## 👀 Preview

Getting a look at the portfolio takes two steps:

| Step | Action |
|:--:|:--|
| 1️⃣ | **Download or clone** this project |
| 2️⃣ | **Open** [`Editkaro Portfolio.html`](./Editkaro%20Portfolio.html) in a modern web browser |

> 🌐 **Stay online for the best experience.** The page loads Tailwind CSS and Google Fonts from their CDNs, so an internet connection keeps everything looking sharp.

---

## ✨ Features

| Feature | Description |
|:--|:--|
| 🏠 **Agency Landing Page** | A clear introduction with prominent calls to action |
| 🗂️ **Filterable Gallery** | Browse work by category — **Shorts**, **Gaming**, **Ads**, and **Anime** |
| 🪟 **Project Detail Modal** | Select any portfolio card to open a detailed view |
| 📋 **Copy-to-Clipboard Contact** | One click copies `contact@editkaro.in`, with an on-page confirmation |
| 🌀 **Scroll Effects** | A compact sticky navigation bar and smooth reveal animations |
| 📱 **Responsive Layout** | Looks great on phones, tablets, and desktops, styled with Tailwind CSS |

### 🎞️ Portfolio Categories

```text
   ┌──────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐
   │ 📱 Shorts │   │ 🎮 Gaming │   │ 📢  Ads   │   │ 🌸 Anime  │
   └──────────┘   └──────────┘   └──────────┘   └──────────┘
         ▲               ▲              ▲              ▲
         └───────────────┴──── Filter ──┴──────────────┘
```

---

## 🚀 Getting Started

### Option A — Open Locally 🖱️

Double-click **`Editkaro Portfolio.html`**, or open it from your browser using **File → Open**.

### Option B — Serve Locally (optional) 🖥️

Have Python installed? Run this from the project folder:

```bash
python -m http.server 8000
```

Then visit 👉 [http://localhost:8000/Editkaro%20Portfolio.html](http://localhost:8000/Editkaro%20Portfolio.html)

> 💡 **Tip:** Serving the page locally mirrors how it behaves on a real web host, and some browsers handle clipboard access more reliably this way.

---

## 📁 Project Structure

```text
Editkaro-Portfolio/
├── Editkaro Portfolio.html   # Main page: markup, embedded styles, project data & interactions
├── Editkaro Portfolio.css    # Additional Google Fonts import
└── README.md                 # Project documentation
```

| File | Purpose |
|:--|:--|
| [`Editkaro Portfolio.html`](./Editkaro%20Portfolio.html) | Main page markup, embedded styles, project data, and interactions |
| [`Editkaro Portfolio.css`](./Editkaro%20Portfolio.css) | Additional Google Fonts import |

---

## 🛠️ Technology

| Layer | Tool |
|:--|:--|
| 🧱 **Structure** | HTML |
| 🎨 **Styling** | Tailwind CSS (via CDN), custom CSS |
| 🔤 **Typography** | Google Fonts — Plus Jakarta Sans |
| ⚡ **Interactivity** | Vanilla JavaScript |

---

## 🎨 Customization

Make the portfolio your own:

<details open>
<summary><b>🗂️ Portfolio Cards</b></summary>

<br>

Edit the `projects` array near the end of `Editkaro Portfolio.html`. Each item defines:

| Property | Purpose |
|:--|:--|
| `title` | The project name shown on the card |
| `category` | The filter it belongs to (Shorts, Gaming, Ads, Anime) |
| `type` | The kind of work |
| `gradient` | The card's background gradient |

</details>

<details>
<summary><b>📧 Contact Email</b></summary>

<br>

Update the email address inside the `copyEmail()` function, then update the matching text in this README.

</details>

<details>
<summary><b>🎨 Visual Style</b></summary>

<br>

Adjust the embedded styles and Tailwind utility classes directly in the HTML file.

</details>

<details>
<summary><b>🔤 Fonts</b></summary>

<br>

The page loads **Plus Jakarta Sans** and **Tailwind CSS** from external CDNs. The separate CSS file contains an additional Google Fonts import.

</details>

---

## 📝 Notes

> [!NOTE]
> The project detail modal is currently a **visual sample** and doesn't play video. Connect a video source and player to make portfolio previews playable.

> [!IMPORTANT]
> The HTML file contains the primary styles and behaviour inline. The separate **CSS file is not currently linked** from the HTML page.

> [!NOTE]
> There is no package manager, build configuration, or automated test suite in this project.

---

## 🗺️ Roadmap

Ideas for taking the portfolio further:

- [ ] ▶️ Embed playable video previews in the project modal
- [ ] 🔗 Link the separate CSS file, or merge it into the HTML
- [ ] 📬 Add a contact form alongside the copy-email action
- [ ] 🖼️ Replace gradients with real project thumbnails
- [ ] 🚀 Deploy to GitHub Pages, Netlify, or Vercel

---

<div align="center">

🎬 **Made as a portfolio website concept for Editkaro.in** 🎬

⭐ *If you like this project, consider giving it a star!* ⭐

</div>
