# 🎵 Soundwave — Music Recommendation Website

A sleek, AI-inspired music recommendation web app with mood-based filtering, genre browsing, trending tracks, and a live now-playing bar.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 🚀 Live Demo

> 
https://rmukheshchandra.github.io/music-recommendation/

---

## 📸 Features

- 🎭 **Mood-Based Recommendations** — Filter songs by Chill, Energetic, Happy, Melancholy, Focus, or Romantic
- 🔍 **Search** — Search by song title, artist, or genre
- 🎸 **Genre Browser** — Filter by Pop, Hip-Hop, Electronic, Indie, R&B, Jazz, Classical, Metal, Lo-fi
- 📈 **Trending Now** — Ranked track list with HOT / NEW badges
- 🌟 **Artist Spotlight** — Featured artist section with follow/unfollow toggle
- 🎧 **Now Playing Bar** — Fixed bottom bar with play/pause, seek, shuffle, and like controls
- 🌙 **Dark Theme** — Cinematic dark UI with animated gradient orbs

---

## 📁 Project Structure

```
soundwave/
│
├── index.html        # Main website file (rename from music-recommender.html)
└── README.md         # Project documentation
```

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/soundwave.git
cd soundwave
```

### 2. Run locally

Just open `index.html` in your browser — no build tools or dependencies needed.

```bash
# On Mac
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

---

## 🌐 Deploy to GitHub Pages

### Step 1 — Rename your file

Make sure your main file is named **`index.html`** (not `music-recommender.html`).

### Step 2 — Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/soundwave.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/soundwave`

> ⚠️ **Common 404 Fix:** Always name your entry file `index.html`. GitHub Pages serves `index.html` by default — any other filename will result in a 404 error.

---

## 🎨 Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure and layout |
| CSS3 | Styling, animations, gradient orbs |
| Vanilla JavaScript | Interactivity, search, filtering |
| Google Fonts | Playfair Display + DM Sans |

---

## 📱 Usage

| Action | How |
|--------|-----|
| Search songs | Type in the search bar and press **Enter** or click **Discover** |
| Filter by mood | Click any mood pill (Chill, Happy, etc.) |
| Filter by genre | Click a genre chip in the Browse Genres row |
| Play a track | Click any song card or track row |
| Like / Shuffle | Use the controls in the Now Playing bar |
| Follow artist | Click **+ Follow** in the Artist Spotlight section |

---

## 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repo, then:
git checkout -b feature/your-feature
git commit -m "Add your feature"
git push origin feature/your-feature
# Open a Pull Request
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ♪ by [mukhesh]https://github.com/rmukheshchandra
