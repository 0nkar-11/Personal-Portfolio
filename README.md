# Onkar Shinde - Student Portfolio Website

Welcome! This is the personal portfolio website for **Onkar Shinde**, Semester 1 (Term 1) Computer Science undergraduate at **Scaler School of Technology** (Bangalore, India).

This project is built from scratch using **pure semantic HTML5 and modern CSS3** with a **Cyan & Fire Orange** theme as a milestone first web development project.

---

## 📁 File Structure

```text
Personal portfolio/
│
├── index.html        # Clean, semantic HTML5 markup (zero inline CSS)
├── style.css         # Modern, responsive CSS styling with variables & dark theme
└── README.md         # Documentation & guide
```

---

## 🚀 How to Open and View Your Website

### Option 1: Direct Browser View (Easiest)
1. Go to your folder: `/home/username
2. /Documents/Web Dev/Personal portfolio/`
3. Double-click **`index.html`** (or right-click and open in Google Chrome / Brave / Firefox).

### Option 2: Live Local Server via Terminal
In your terminal, navigate to this directory and run:
```bash
python3 -m http.server 8000
```
Then open your browser and visit: `http://localhost:8000`

---

## 🎨 How to Personalize Further

- **Add your real photo**:
  In `index.html`, inside `.avatar-wrapper`, replace the `<svg>...</svg>` with:
  ```html
  <img src="my-photo.jpg" alt="Onkar Shinde" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;" />
  ```
- **Connected Profiles**:
  Your GitHub (`https://github.com/0nkar-11`) and SST email (`onkar.26bcs10819@sst.scaler.com`) are configured across the hero section and contact cards.
- **Theme Colors (Cyan & Fire Orange)**:
  Configured in `style.css` using CSS custom properties:
  ```css
  --accent-cyan: #00d2ff;   /* Electric Cyan */
  --accent-fire: #ff5722;   /* Fire Orange */
  ```
