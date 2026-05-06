# RINASTAMILYT – Personal Gaming Website

## 📁 Folder Structure
```
RINASTAMILYT/
├── index.html        ← Main page
├── css/
│   └── style.css     ← All styles
├── images/           ← Put YOUR images here
│   ├── profile.jpg   ← Your photo (About section)
│   ├── shot1.jpg     ← Gallery image 1
│   ├── shot2.jpg     ← Gallery image 2
│   ├── shot3.jpg     ← Gallery image 3
│   ├── shot4.jpg     ← Gallery image 4
│   ├── shot5.jpg     ← Gallery image 5
│   └── shot6.jpg     ← Gallery image 6
└── README.md         ← This file
```

---

## 🖼️ How to Add YOUR Images

### Profile / About Photo
1. Put your photo in the `images/` folder, name it `profile.jpg`
2. In `index.html`, find the About section and **replace** this:
   ```html
   <div class="img-placeholder">...</div>
   ```
   With this:
   ```html
   <img src="images/profile.jpg" alt="Rinas" />
   ```

### Gallery Screenshots
1. Put your game screenshots in `images/` folder
2. In each gallery card, **replace** the placeholder div:
   ```html
   <div class="g-placeholder">📸<br/>images/shot1.jpg</div>
   ```
   With an actual image tag:
   ```html
   <img src="images/shot1.jpg" alt="GTA V Screenshot" />
   ```

---

## 🎬 How to Add YouTube Videos

1. Go to your YouTube video
2. Copy the video ID from the URL  
   Example: `https://www.youtube.com/watch?v=**dQw4w9WgXcQ**`  
   → The ID is `dQw4w9WgXcQ`
3. In `index.html`, replace `VIDEO_ID_1`, `VIDEO_ID_2`, `VIDEO_ID_3` with your actual IDs:
   ```html
   src="https://www.youtube.com/embed/dQw4w9WgXcQ"
   ```

---

## 🔗 How to Add Your Social Links

Find these lines in `index.html` and update the `href` values:
```html
<!-- YouTube – already set to your channel -->
<a href="https://www.youtube.com/@RINASTAMILYT" ...>

<!-- Instagram – add your link -->
<a href="https://instagram.com/yourhandle" ...>

<!-- Discord – add your server invite -->
<a href="https://discord.gg/yourinvite" ...>
```

---

## 🎨 Changing Colors (Optional)

Open `css/style.css` and edit the CSS variables at the top:
```css
:root {
  --accent: #ff3b3b;   /* Red – main accent color */
  --neon:   #00f5d4;   /* Cyan – highlights */
  --bg:     #09090f;   /* Dark background */
}
```

---

## 🌐 Hosting (Free Options)
- **GitHub Pages** – Free, easy, fast
- **Netlify** – Drag and drop your folder
- **Vercel** – Great for personal sites

---

Made for **RINASTAMILYT** 🎮🇱🇰
