# 🎂 Happy Birthday Didi! — Website

A personalised birthday website (same as the one made for Gungun) — now for **Didi** 💜

## What's inside

| File | What it is |
|---|---|
| `index.html` | The main website (photo collage → gifts → cake cutting page) |
| `message_for_didi.html` | The heartfelt message gift (replaces the old pets message) |
| `photo1.jpg` … `photo16.jpg` | Collage photos — **replace with Didi's photos** |
| `cake-video.mp4` | 12AM birthday video — **replace with your video** |
| `special-video.mp4` | The special video gift — **replace with your video** |
| `Music.mp3` | Background music (currently same as original — swap if you want) |
| `gift_*.jpg` | Gift images (pani puri / rasmalai / chocolate / flowers) |

## ✏️ How to personalise (3 steps)

1. **Photos** → rename Didi's 16 photos to `photo1.jpg`, `photo2.jpg` … `photo16.jpg`
   (placeholders have a number tag in the corner) and replace the files.
   Any photo format works (`.jpg`, `.png`, `.jpeg`) — just keep the name and edit the
   `<img src="photoN.jpg">` lines in `index.html` if you change extensions.
2. **Videos** → replace `cake-video.mp4` and `special-video.mp4` with your real videos
   (keep the same filenames).
3. **Music (optional)** → replace `Music.mp3` with any song you like.

### Easy tweaks inside `index.html`
- **Name on card:** search for `<div class="card-name">Didi!</div>`
- **Coupon codes:** search for `DIDIPURIYAN`, `DIDIMALAI`, `DIDICHOCO`
- **Gift messages & T&C:** search for `giftData`
- **Message to Didi:** edit the lines in `message_for_didi.html` (each `<div class="line">…</div>`)

## 🌍 How to put it online (GitHub Pages, like the original)

1. Create a new GitHub repo (e.g. `HappyBirthDayDidi`).
2. Upload **all** files from this folder (keep the same names).
3. Repo → **Settings → Pages** → Source: `main` branch, `/ (root)` → Save.
4. Wait 1–2 minutes → your site will be live at
   `https://YOUR-USERNAME.github.io/HappyBirthDayDidi/`

## 💡 Tips

- Video sizes: try to keep each video under ~25 MB so the page loads fast on mobile.
- Test on your phone before sending it to Didi 📱
- Send the link at exactly 12AM for full effect 😄
