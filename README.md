# Tech News RSS Aggregator

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%26%20CSS3-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20ES6%2B-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Feed Service](https://img.shields.io/badge/Feeds-Live%20RSS%20Aggregator-orange.svg)](#)

English | [فارسی](README_FA.md)

A lightweight, modern, client-side technology news aggregator dashboard that consumes and displays live RSS feeds from leading Iranian and global tech publications with real-time timestamps and an ambient background.

---

## 🌟 Overview

Staying up to date with fast-moving tech news often involves checking multiple websites or heavy RSS reader apps. This project delivers an instant, zero-install web dashboard that curates domestic and international technology headlines in a single, elegant screen.

Key highlights:
- **Zero Backend Required**: Runs 100% in the client browser using asynchronous JavaScript feed parsing.
- **Dual Tab Architecture**: Instantly switch between domestic (Iran) and international tech publications.
- **Real-Time Timestamps**: Displays publication hours and minutes in clean badges alongside headline links.
- **Persian Calendar Integration**: Native localized date display using browser `Intl.DateTimeFormat`.
- **Dynamic Video Background**: Ambient high-definition looping video background with glassmorphism feed containers.

---

## ✨ Integrated Feed Sources

| Region / Tab | Publications & Feeds |
| :--- | :--- |
| **Domestic (Iran)** | • [Zoomit](https://www.zoomit.ir) (`/feed`)<br>• [Digiato](https://digiato.com) (`/feed`)<br>• [Techna News](https://techna.news) (`/feed`)<br>• [Technolife Blog](https://www.technolife.ir/blog) (`/feed`) |
| **International (World)** | • [Wired](https://www.wired.com) (`/feed`)<br>• [TechCrunch](https://techcrunch.com) (`/feed`)<br>• [TechRadar](https://www.techradar.com) (`/rss`)<br>• [CNET](https://www.cnet.com) (`/rss/all`) |

---

## 🚀 Getting Started

### Prerequisites

A modern web browser (Chrome, Firefox, Edge, Safari). No build tools, compilers, or Node.js required!

### Running the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/soheilabbasnia/rss.git
   cd rss
   ```

2. **Serve locally** (recommended for local HTTP origin):
   ```bash
   # Using Python 3 built-in HTTP server:
   python3 -m http.server 8080
   ```
   Or simply double-click and open `index.html` directly in your browser.

3. Navigate to `http://localhost:8080`.

---

## 📁 Project Structure

```text
rss/
├── assets/
│   ├── css/
│   │   ├── normalize.css    # CSS reset & consistency
│   │   └── style.css        # Dashboard styling, grid layout & glass effects
│   ├── js/
│   │   └── app.js           # RSS fetcher, date formatter & tab switcher
│   └── img/
│       └── background.mp4   # Looping ambient background video
├── index.html               # Main dashboard web page
├── LICENSE                  # MIT License
└── README.md                # Project documentation
```

---

## 🤝 Contributing

Contributions, additional feed sources, and layout improvements are welcome!
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/add-new-feed`).
3. Commit your changes (`git commit -m 'Add The Verge RSS feed'`).
4. Push to the branch (`git push origin feature/add-new-feed`).
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
Free and open-source for personal and educational use.
