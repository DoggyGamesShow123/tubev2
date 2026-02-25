# YouTube Watcher — Animated Background + Snow + Privacy‑Enhanced Embed

A single‑file site (`index.html`) that lets you paste a YouTube link, extracts the video ID, and reloads a **small 16:9** embed using **YouTube’s privacy‑enhanced domain**. The page features a soft **animated gradient background**, a **lightweight falling‑snow canvas**, and an **ambient background video** (muted by default) with a **corner toggle** to control its audio.

> No frameworks. No build step. Just open `index.html`.

---

## ✨ Features

- **Paste & Watch**: Accepts `watch?v=...`, `youtu.be/...`, `/shorts/...`, `/embed/...`, or a bare 11‑char ID.  
- **Privacy‑Enhanced Embed**: Uses `https://www.youtube-nocookie.com/embed/{ID}` to reduce tracking and keep any ads non‑personalized.  
- **Compact Player**: Responsive **16:9** container with a subtle card‑like look.  
- **Animated Background**: CSS gradient that slowly shifts hues with glow accents.  
- **Snow Effect**: Efficient `<canvas>` animation, density scales with viewport; respects **`prefers-reduced-motion`**.  
- **Ambient Background Video**: Autoplays, loops, and stays **unselectable & behind** content; **starts muted** for autoplay reliability.  
- **Audio Toggle**: Top‑right 🔇/🔊 button that **only** affects the background video (not YouTube).  
- **Keyboard Friendly**: Press **Enter** in the URL field to start watching.

---

## 📁 File Layout
