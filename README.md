# ⚽ Fixtures

> Live sports fixtures. No fluff.

A lightweight web application that displays upcoming and live sports fixtures with countdowns, live score updates, search, and pinning functionality—all without requiring API keys.

---

## ✨ Features

- ⚽ Football fixtures (Premier League, Champions League, La Liga, Bundesliga, Serie A, Ligue 1, FIFA World Cup)
- 🏎️ Formula 1 sessions
- 🥊 UFC events
- ⏳ Live countdown timers
- 🔴 Live match indicators
- 📌 Pin your favorite fixtures
- 🔍 Search by team, league, or venue
- 🌐 One-click Google search for any fixture
- ⌨️ Command Palette (`⌘K`)
- 🖥️ ASCII scoreboard mode
- 🔄 Auto refresh every 45 seconds
- 🌙 Modern dark UI inspired by developer tools

---

## 📸 Preview
<img width="1890" height="906" alt="image" src="https://github.com/user-attachments/assets/f9c9d779-fc65-415d-bec6-fb7a576335ff" />

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Fixtures.git
```

Move into the project:

```bash
cd Fixtures
```

Start a local server:

```bash
python -m http.server
```

or

```bash
python3 -m http.server
```

Open your browser and visit:

```
http://localhost:8000
```

> **Do not open the HTML file directly using `file://`**, as browsers block API requests from local files.

---

## 📡 Data Sources

This project uses publicly available APIs:

- ESPN Soccer Scoreboard
- ESPN MMA Scoreboard
- OpenF1 API

No API keys are required.

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- ESPN Public APIs
- OpenF1 API

---

## 🎮 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `/` | Focus search |
| `⌘K` | Open command palette |
| Refresh | Reload live data |

---

## 📂 Project Structure

```
Fixtures/
│
├── fixtures.html
├── README.md
└── preview.png
```

---

## 💡 Future Improvements

- Team logos
- Multiple sports support (NBA, Cricket, Tennis)
- Notifications for favorite matches
- PWA support
- Mobile-first gestures
- Timezone selection
- Dark/Light themes
- Offline caching

---

## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**AM**

Built with ❤️ for sports fans who just want the fixtures.
