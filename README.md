# Exam Timer

A simple, elegant countdown timer for exams — distraction-free and TA-friendly.

📍 [Live demo](https://zander-m.github.io/exam_timer/)  
📱 Scan the QR code to use it directly on your phone:  
![QR Code](qr_code.png)

---

## ✨ Features

- 🕒 **Clean countdown interface** — no ads, no clutter.
- 📝 **Markdown notes editor** — embed exam info or announcements.
- 💾 **Persistent data** — countdown and notes saved locally per device.
- 🕶️ **Dimmed seconds** — less visual noise; seconds light up in the final minute.
- 🎉 **Confetti celebration** — visual cue when time's up.
- 🔊 **Optional alarm** — gentle sound at exam end.

---

## 🔧 Tech Stack

- Pure HTML, CSS, and JavaScript
- `localStorage` for persistence
- [`marked.js`](https://github.com/markedjs/marked) for Markdown rendering
- [`canvas-confetti`](https://www.npmjs.com/package/canvas-confetti) for visual effects

---

## 📦 Deployment

This project is fully static and hosted on GitHub Pages.  
To deploy your own version:

```bash
git clone https://github.com/Zander-M/exam_timer
cd exam_timer
# push to a GitHub repo with Pages enabled, or open index.html locally