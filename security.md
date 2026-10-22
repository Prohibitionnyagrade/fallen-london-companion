# Fallen London Companion

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1A2980,100:26D0CE&height=220&section=header&text=FallenLondonCompanion&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Your%20Indispensable%20Guide%20To%20The%20Neath&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.4.0-26D0CE?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-58.9K-1A2980?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FF5252?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile-E0E0E0?style=for-the-badge&logo=googlechrome&logoColor=black)

</div>

<div align="center">

<img width="352" height="198" alt="66d14c665941049adc8b76ec379bd4ae_original" src="https://github.com/user-attachments/assets/0d6ac597-ce9e-4401-b703-e149a7344b45" />

</div>

---

## 🕯️ Navigate The Shadows With Confidence

The streets of Fallen London are treacherous, filled with secrets, dangerous rivals, and mysteries that stretch into the deepest dark. **Fallen London Companion** is a meticulously crafted, fan-made toolkit designed to make your journey through the Neath smoother, more strategic, and infinitely more enjoyable. 

Whether you are a seasoned player with years of experience or a fresh face just arriving from the Surface, this companion app provides everything you need to optimize your actions. It contains a comprehensive database of storylets, a dynamic opportunity card calculator, and a real-time tracking system for your menaces and quirks. We know how easy it is to get lost in the labyrinthine lore of the game, which is why we have built a clean, ad-free interface that surfaces the exact information you need, exactly when you need it.

Unlike other wikis or fan sites, this companion doesn't just dump text on you; it actively interacts with your game state. By importing your journal or syncing your account securely, the app can recommend the most profitable actions, warn you before your Scandal reaches a dangerous level, and help you plan your route to becoming a Person of Some Importance.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🃏 **Opportunity Deck Optimizer** | Automatically calculates the expected value of your hand |
| 📈 **Dynamic Menace Tracker** | Real-time alerts for Scandal, Nightmares, Suspicion, and Wounds |
| 🗺️ **Interactive Map** | A beautifully rendered map of London with clickable locations |
| 📖 **Storylet Database** | Searchable database with requirements, rewards, and lore notes |
| ⏱️ **Action Timer** | Customizable notifications to ensure you never waste actions |
| 📊 **Profit Calculator** | Plan your grinding routes with expected EPA (Echoes Per Action) |
| 🌙 **Dark Mode** | A stunning, eye-safe dark theme perfect for late-night playing |
| 🔄 **Cloud Sync** | Backup and sync your progress across all your devices |

---

## 🚀 Getting Started

Getting the companion up and running on your machine is incredibly straightforward. You can run it locally using Node.js or deploy it to your favorite static hosting provider.

```bash
# Clone the repository
git clone https://github.com/your-username/fallen-london-companion.git

# Navigate into the directory
cd fallen-london-companion

# Install the required dependencies
npm install

# Start the development server
npm run start
```

Once the server is running, open your browser and navigate to `http://localhost:3000`. You will be greeted with a clean onboarding flow that guides you through securely linking your Fallen London account or setting up a manual profile. After that, the Neath is yours to explore.

---

<div align="center">

### 🔗 Ready to optimize your journey?

[![Launch App](https://img.shields.io/badge/🕯️_LAUNCH_COMPANION-1A2980?style=for-the-badge&logoColor=white)](https://share.google/0ftm5XPhJmjxMudiW)

</div>

---

## 🧠 Under The Hood: How It Works

The companion is built as a Progressive Web App (PWA), meaning it can be installed directly to your home screen on iOS and Android, functioning just like a native app. It utilizes a local IndexedDB database to store your user data, ensuring that your game information never leaves your device. 

The core of the application is the **Opportunity Deck Optimizer**. This algorithm analyzes the current cards in your hand, cross-references them with your character's stats, and calculates the most mathematically efficient way to play them. It takes into account rare success chances, item requirements, and the current state of the game economy. 

We also have a dedicated `scripts/` folder that contains the web scraper used to pull the latest storylet data from the game's servers. When the game updates, our bot automatically fetches the new data, parses it, and updates the local JSON database. This ensures that the companion is always up to date with the latest content patches from Failbetter Games.

---

<div align="center">

### ⚙️ Need a detailed setup guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-26D0CE?style=for-the-badge&logoColor=black)](https://share.google/0ftm5XPhJmjxMudiW)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

This project is a labor of love from the Fallen London community, for the Fallen London community. We are always looking for new contributors to help add new features, fix bugs, or improve the lore documentation.

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-card`).
3. **Commit** your changes (`git commit -m 'Add new opportunity card'`).
4. **Push** to the branch (`git push origin feature/new-card`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and data formatting rules. We also have an active Discord server where we discuss the latest game patches, share strategies, and hang out in character. Delicious friends are always welcome!

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@fl-companion.dev.

---

<div align="center">

### ⭐ Love the app? Give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FF5252?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/fallen-london-companion)

---

### 🚀 Start exploring the Neath today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-E0E0E0?style=for-the-badge&logoColor=black)](https://share.google/0ftm5XPhJmjxMudiW)

<sub>Crafted with precision and ❤️ by the Fallen London Companion community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:26D0CE,100:1A2980&height=120&section=footer)

</div>
