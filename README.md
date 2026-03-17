# I Love CV 📄

**A free, no-signup, no-watermark resume and cover letter builder with ATS score checking.**

Built for students and job seekers around the world.

🔗 **Live site:** [ilovecv.vercel.app](https://ilovecv.vercel.app)

---

## Features

- **5 professional templates** — Classic, Modern, Elegant, Minimal, Bold
- - **ATS score checker** — paste a job description and instantly see how well your resume matches it, which keywords are found, and which are missing
- **Duplicate sections** — copy an existing experience or education entry in one click
- **Cover letter maker** — live preview with PDF and DOCX export
- **Skill proficiency bars** — set your own level per skill (Modern template)
- **Profile photo** — optional, stored locally in your browser
- **PDF export** — via browser print, clean A4 output
- **DOCX export** — downloads a proper Word document, no library required
- **Auto-save** — everything saves to localStorage, your data never leaves your device
- **No signup** — open the site and start building immediately
- **No watermark** — your resume is yours, completely clean

---

## How it works

The entire app is a single HTML file. No backend, no database, no server. Everything runs in your browser.

- Your data is saved in `localStorage` — it stays on your device
- PDF export uses the browser's built-in print function
- DOCX export uses JSZip to build a Word file entirely in the browser
- Deploying is as simple as uploading one HTML file to any static host

---

## Tech stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Export (PDF) | Browser print API |
| Export (DOCX) | JSZip (CDN) |
| Fonts | Google Fonts |
| Hosting | Vercel (free tier) |

No frameworks. No build step. No dependencies to install.

---

## Run locally

Just download `index.html` and open it in your browser. That's it.

```bash
# Or clone the repo
git clone https://github.com/yourusername/ilovecv.git
cd ilovecv
# Open index.html in your browser
```

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | The resume and cover letter builder |
| `about.html` | About the creator + support page |

---

## Support

If I Love CV helped you land a job or saved you time, consider supporting via eSewa:

**eSewa:** `9823418816`

---

## License

MIT — free to use, modify, and share.

---

Built with ❤️ from Kathmandu, Nepal.
