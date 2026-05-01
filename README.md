# Thilina Kushan Karunathunga — Personal & Professional Website

A professional personal portfolio website for **Thilina Kushan Karunathunga** — Area Marketing Executive at Cargills Ceylon PLC and Founder of **Lions Ceylonic Tours**.

## 🌐 Live Site
Hosted via GitHub Pages: `https://[your-username].github.io/[repo-name]/`

---

## 📁 File Structure

```
kushan-website/
├── index.html                  ← Main website (single page)
├── assets/
│   ├── images/
│   │   ├── profile.jpg         ← Professional headshot
│   │   ├── lions-logo.jpg      ← Lions Ceylonic Tours logo
│   │   ├── tour-1.jpg          ← Tour photography (8 images)
│   │   │   ...
│   │   ├── life-1.jpg          ← Personal gallery (6 images)
│   │   │   ...
│   └── logos/
│       ├── getyourguide.jpg
│       ├── tripadvisor.png
│       └── viator.png
└── README.md
```

---

## 🚀 How to Host on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create an account).
2. Click the **+** icon → **New repository**.
3. Name it `kushan-portfolio` (or any name you prefer).
4. Set it to **Public**.
5. Click **Create repository**.

### Step 2 — Upload Your Files
**Option A — GitHub Web Interface (easiest):**
1. Open your new repository.
2. Click **Add file → Upload files**.
3. Drag and drop the entire `kushan-website` folder contents:
   - Upload `index.html`
   - Upload the `assets/` folder with all sub-folders
4. Click **Commit changes**.

**Option B — Git Command Line:**
```bash
cd kushan-website
git init
git add .
git commit -m "Initial website upload"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/kushan-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings → Pages** (left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Set branch to `main` and folder to `/ (root)`.
4. Click **Save**.
5. After 1–2 minutes, your site will be live at:
   `https://YOUR-USERNAME.github.io/kushan-portfolio/`

---

## ✏️ Updating Your Site

To update content (text, images, links):
1. Edit `index.html` in any text editor (Notepad, VS Code, etc.).
2. Replace image files in `assets/images/` as needed.
3. Re-upload to GitHub — changes go live within minutes.

---

## 📞 Contact Details in Site
- Phone: +94 77 553 3276
- WhatsApp (Tours): +94 77 956 5880
- Email: Kushan.ufs@gmail.com
- Tours Website: www.lionsceylonictours.com

---

*Built with pure HTML & CSS — no frameworks, no dependencies.*
