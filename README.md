# 🌧️ Monsoon Mist

> *Where the monsoon comes home.*

A cinematic architectural presentation — a moody, atmospheric web experience showcasing a residence designed for the rain. Built with pure HTML, CSS, and JavaScript. No build step. No dependencies. Just drop and deploy.

---

## ✨ Features

- 🎬 **Cinematic scroll experience** — each image revealed like a film
- 🌧️ **Live rain canvas** — gentle falling raindrops throughout
- ☁️ **Atmospheric mist & grain** — subtle layered fog and film grain
- 🔥 **Warm cursor glow** (desktop) — amber light follows the cursor
- 🖼️ **Click any image for fullscreen** — smooth lightbox with keyboard + swipe navigation
- 📱 **Mobile-first responsive** — adapts beautifully on every device
- 🔊 **Optional rain ambience** — toggle a soft rain soundtrack
- ⚡ **Single HTML file** — no build, no npm, just open
- 🎨 **Editorial typography** — Cormorant Garamond + Fraunces + Jost

---

## 📁 Project Structure

```
monsoon-mist/
├── index.html              ← The entire site (single file)
├── README.md               ← This file
└── images/
    ├── 01-rain-puddle.png
    ├── 02-aerial-sunrise.png
    ├── 03-mosque-landscape.png
    ├── 04-palm-bokeh.png
    ├── 05-roof-mosque-view.png
    ├── 06-wet-pavement.png
    ├── 07-aerial-top.png
    ├── 08-hero-front-elevation.png    ← The hero
    ├── 09-house-sunset.png
    ├── 10-entrance-glow.png
    ├── 11-house-foggy.png
    ├── 12-roof-detail.png
    ├── 13-wall-lamp.png
    ├── 14-facade-detail.png
    ├── 15-window-glow.png
    ├── 16-door-closeup.png
    ├── 17-aerial-entrance.png
    ├── 18-misty-evening.png
    ├── 19-aerial-mosque-context.png   ← The mosque story
    ├── 20-option-beige.png            ← Variation I
    └── 21-option-dark.png             ← Variation II
```

---

## 🚀 Deployment (3 Steps)

### Step 1 — Push to GitHub

```bash
# In the project folder
git init
git add .
git commit -m "Initial commit — Monsoon Mist"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/monsoon-mist.git
git push -u origin main
```

### Step 2 — Deploy on Vercel

1. Go to **[vercel.com](https://vercel.com)** and sign in (with GitHub)
2. Click **"Add New" → "Project"**
3. Select your `monsoon-mist` repo
4. Click **Deploy** — that's it. No config needed.
5. Vercel gives you a live link like `https://monsoon-mist.vercel.app`

### Step 3 — Share the link 🌧️

That's it. The site is live. Send the link to clients on WhatsApp, embed it anywhere, share on Instagram.

---

## ✏️ Customising Content

### Change a tagline
Open `index.html`, search for the line you want to change (e.g. `Cradled by mist and minarets`), edit it. Save. Push to GitHub. Vercel auto-deploys.

### Replace an image
Drop a new image into `/images/` with the **exact same filename** as the old one. Push to GitHub. Done.

### Add or remove a scene
Search `<!-- SCENE` in `index.html` — each scene is a self-contained block. Copy a block to add one. Delete a block to remove one. Save. Push.

### Change project name or hero tagline
Search `Monsoon Mist` and `Where the monsoon comes home` in `index.html`.

---

## 📱 Browser Support

Works on every modern browser. Tested on:
- Chrome / Edge / Safari / Firefox (desktop)
- iOS Safari, Chrome Android (mobile)

---

## 🎨 Design Notes

- **Theme**: Pure black (`#0a0807`) + warm amber (`#f4a261`, `#ffd89b`)
- **Body font**: Jost (clean, modern)
- **Headline serif**: Fraunces (variable, characterful)
- **Italic serif**: Cormorant Garamond (poetic, editorial)
- **Mood**: Cinematic. Atmospheric. Patient.

---

## 💡 Tips

- The site looks best in dark rooms 🌙
- For the full experience, click the **♪ button** (bottom right) to enable rain ambience
- Try **arrow keys** when an image is fullscreen — they work for navigation
- On mobile, **swipe left/right** in the lightbox to navigate

---

*Built with care, for the rain.*
