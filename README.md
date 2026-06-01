# 📚 StudyDesk — JEE Study Planner PWA

A **Progressive Web App** (PWA) designed for JEE aspirants to organize their study life with schedules, assignments, habits, focus sessions, and reading tracking.

## ✨ Features

- 📅 **Daily Schedule** — Time blocks with color-coded categories
- 📋 **Assignment Tracker** — Deadlines, priority levels, course tagging
- 🔥 **Habit Tracker** — Weekly habit progress with visual indicators
- 📚 **Course Progress** — Visual progress circles for each course
- ⏱ **Pomodoro Timer** — Focus, short break, and long break modes
- 🧠 **Brain Dump** — Quick note-taking for random ideas
- 🗓 **Weekly Calendar** — Event planning and overview
- 📖 **Reading List** — Track currently reading, next up, and queued books
- 💾 **Offline Support** — Works completely offline with IndexedDB persistence
- 📱 **Installable** — Install as a native app on mobile and desktop

## 🚀 Quick Start

### Online (GitHub Pages)
1. Visit: **[https://DOTBotdotcom.github.io/Studydesk/](https://DOTBotdotcom.github.io/Studydesk/)**
2. Click the **"Install"** button to add to your home screen

### Local Development
```bash
# Clone the repo
git clone https://github.com/DOTBotdotcom/Studydesk.git
cd Studydesk

# Start a local server
npx http-server -p 8000 -c-1

# Visit: http://localhost:8000
```

## 📋 File Structure

```
Studydesk/
├── index.html       # Main app UI (responsive, single-page)
├── manifest.json    # PWA metadata (icons, theme, shortcuts)
├── sw.js           # Service Worker (offline caching)
├── package.json    # Project metadata
├── .gitignore      # Git exclusions
└── README.md       # This file
```

## 🛠 Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (no frameworks)
- **Storage:** IndexedDB (local persistence)
- **PWA:** Service Worker + Web App Manifest
- **Icons:** Emoji + SVG
- **Fonts:** Google Fonts (Fraunces serif, DM Sans sans-serif)
- **Deployment:** GitHub Pages

## 🎨 Design Highlights

- **Warm Color Palette:** Cream, amber, sage green, rose, teal
- **Mobile-First:** Optimized for phones, tablets, and desktops
- **Accessible:** Dark/light aware, touch-friendly controls
- **Offline-First:** All data stored locally, works without internet

## 📲 Installation

### Mobile (iOS/Android)
1. Open in browser
2. Tap **Share** (Safari) or **Menu** (Chrome)
3. Select **"Add to Home Screen"** / **"Install"**
4. App opens fullscreen like a native app

### Desktop (Chrome/Edge)
1. Click the **Install** button in top-left corner
2. Or use **Menu** → **"Install StudyDesk"**
3. Opens in a standalone window

## 💾 Data Persistence

- **All data is stored locally** in IndexedDB
- No cloud sync — only on your device
- **Export Option** (coming soon)
- Data persists across app updates

## 🔄 Offline Functionality

- Browse all content without internet
- All features work offline
- Changes sync when reconnected
- Service Worker caches static assets

## 🎯 Keyboard Shortcuts (Planned)

- `Ctrl/Cmd + S` — Force save
- `?` — Help modal
- `Tab` — Navigate between sections

## 📝 Usage Tips

### Schedule
- Add recurring time blocks for consistent routines
- Use tags to categorize (Class, Study, Home, Health)
- Rearrange by manually editing the app

### Assignments
- Mark urgent to highlight in red
- Check off when completed
- Includes course and due date info

### Habits
- Track daily with ✓ / – indicators
- See weekly progress at a glance
- Reset every Sunday

### Pomodoro
- **Pomodoro (25 min)** — Focus work
- **Short Break (5 min)** — Quick rest
- **Long Break (15 min)** — Extended break
- Edit subject before starting

### Brain Dump
- Capture quick thoughts
- Delete when implemented
- No organization needed

## 🌐 Deployment (GitHub Pages)

This project is deployed on GitHub Pages:

1. **Main branch** contains production files
2. **Automatic deploy** on push to `main`
3. **Live URL:** `https://DOTBotdotcom.github.io/Studydesk/`

To deploy your own fork:
```bash
# 1. Fork the repo
# 2. Enable GitHub Pages in Settings
# 3. Select 'main' branch as source
# 4. Access at: https://<your-username>.github.io/Studydesk/
```

## 🔐 Privacy

- ✅ **No tracking** — No analytics or external calls
- ✅ **No ads** — Completely ad-free
- ✅ **No login** — No account required
- ✅ **Open source** — Code is public and transparent

## 🐛 Known Limitations

- No cloud sync between devices
- No collaborative features
- No export/import UI (but data is in IndexedDB)
- Limited browser support (modern browsers only)

## 🚀 Roadmap

- [ ] Data export (JSON backup)
- [ ] Dark mode toggle
- [ ] Custom color themes
- [ ] Notifications for deadlines
- [ ] Time zone support
- [ ] Multiple study profiles
- [ ] PDF export for schedules

## 🤝 Contributing

Found a bug? Have an idea? Open an issue or PR!

```bash
git clone https://github.com/DOTBotdotcom/Studydesk.git
git checkout -b feature/your-idea
# Make changes...
git push origin feature/your-idea
```

## 📄 License

MIT — Use freely, modify, distribute.

## 🙏 Acknowledgments

- Built for JEE aspirants
- Inspired by modern productivity apps
- Designed with ❤️ for better study habits

---

**Need help?** Open an issue: [GitHub Issues](https://github.com/DOTBotdotcom/Studydesk/issues)

**Live Demo:** [StudyDesk PWA](https://DOTBotdotcom.github.io/Studydesk/)
