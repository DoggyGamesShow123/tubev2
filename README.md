# YouTube Watcher — Animated Background + Snow + Privacy‑Enhanced Embed

A single‑file site that lets you paste a YouTube link, extracts the video ID, and reloads a **small 16:9** embed using **YouTube’s privacy‑enhanced domain**. It features a soft **animated gradient background**, a **lightweight falling‑snow canvas**, and an **ambient background video** (muted by default) with a **corner toggle** to control its audio.

> No frameworks. No build step. Just open `index.html`.

---

## 🚀 Live Demo

**👉 Try it here:** https://doggygamesshow123.github.io/tubev2/

---

## ✨ Features

- **Paste & Watch**  
  Accepts `watch?v=...`, `youtu.be/...`, `/shorts/...`, `/embed/...`, or a bare 11‑char ID, then swaps the embed to play automatically.

- **Privacy‑Enhanced Embed**  
  Uses `https://www.youtube-nocookie.com/embed/{ID}` to reduce tracking and keep any ads non‑personalized.

- **Compact Player**  
  Responsive **16:9** container (kept small) with subtle depth and shadows.

- **Animated Background**  
  CSS gradient that slowly shifts hues, plus soft radial glow accents.

- **Snow Effect**  
  Efficient `<canvas>` animation, density scales with viewport, respects **`prefers-reduced-motion`**.

- **Ambient Background Video**  
  Autoplays, loops forever, **unselectable**, and rendered **behind** the UI/snow; **starts muted** for autoplay reliability.

- **Audio Toggle (🔇/🔊)**  
  A floating button that **only controls the background video’s audio** (the YouTube embed is unaffected).

- **Keyboard Friendly**  
  Press **Enter** in the URL field to start watching.

---

## 📁 Project Layout

``
