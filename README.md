# Editkaro.in — Video Editing Portfolio

A polished, single-page portfolio concept for **Editkaro.in**, a social-first video editing and post-production agency. The site presents selected work across gaming, advertising, anime, and short-form content in a dark, vibrant layout.

> **No build step required.** Open the HTML file in a browser to explore the portfolio.

## Contents

- [Preview](#preview)
- [Features](#features)
- [Getting started](#getting-started)
- [Project structure](#project-structure)
- [Technology](#technology)
- [Customization](#customization)
- [Notes](#notes)

## Preview

1. Download or clone this project.
2. Open [`Editkaro Portfolio.html`](./Editkaro%20Portfolio.html) in a modern web browser.

For the best experience, keep an internet connection available so the page can load Tailwind CSS and Google Fonts from their CDNs.

## Features

- **Agency landing page** with a clear introduction and calls to action.
- **Filterable project gallery** with categories for Shorts, Gaming, Ads, and Anime.
- **Project detail modal** that opens when a portfolio card is selected.
- **Copy-to-clipboard contact action** for `contact@editkaro.in`, with an on-page confirmation.
- **Scroll effects** including a compact sticky navigation bar and reveal animations.
- **Responsive layout** styled with Tailwind CSS utility classes.

## Getting started

### Open locally

Double-click `Editkaro Portfolio.html`, or open it from your browser using **File → Open**.

### Serve locally (optional)

If you have Python installed, run this from the project folder:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/Editkaro%20Portfolio.html](http://localhost:8000/Editkaro%20Portfolio.html).

## Project structure

| File | Purpose |
| --- | --- |
| [`Editkaro Portfolio.html`](./Editkaro%20Portfolio.html) | Main page markup, embedded styles, project data, and interactions |
| [`Editkaro Portfolio.css`](./Editkaro%20Portfolio.css) | Additional Google Fonts import |

## Technology

- HTML
- Tailwind CSS via CDN
- CSS and Google Fonts
- Vanilla JavaScript

## Customization

- **Portfolio cards:** Edit the `projects` array near the end of `Editkaro Portfolio.html`. Each item defines a title, category, type, and gradient.
- **Contact email:** Update the email in the `copyEmail()` function and the matching text in this README.
- **Visual style:** Adjust the embedded styles and Tailwind classes in the HTML file.
- **Fonts:** The page loads Plus Jakarta Sans and Tailwind CSS from external CDNs. The separate CSS file contains an additional Google Fonts import.

## Notes

- The project detail modal is currently a visual sample; it does not play video. Connect a video source and player to make portfolio previews playable.
- The HTML includes the primary page styles and behavior inline. The separate CSS file is not currently linked from the HTML page.
- There is no package manager, build configuration, or automated test suite in this project.

---

Made as a portfolio website concept for Editkaro.in.
