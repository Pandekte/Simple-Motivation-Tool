# Motivation Tool with Daily Quotes & Age Counter

![Chrome Web Store](https://chromewebstore.google.com/detail/motivation-tool-with-quot/omcalcehddblccgmlmjdjapmahcibojj)

Stay inspired every day with the **Motivation Tool - Chrome extension**! Designed to seamlessly integrate into your browsing experience, this powerful and user-friendly tool delivers daily motivational quotes right to your browser. Simply click the extension icon or let the quotes appear automatically at your preferred intervals to maintain motivation throughout your day.

---

## Table of Contents

- [✨ Features](#-features)
- [🔧 How to Use](#-how-to-use)
- [🚀 What’s New](#-whats-new)
- [🔮 Coming Soon](#-coming-soon)
- [💻 Tech Stack](#-tech-stack)
- [📂 Project Structure](#-project-structure-gist)
- [🙌 Contact & Contributing](#-contact--contributing)


---

## ✨ Features

- **📌 Pin for Easy Access**
  - Pin the extension to your Chrome toolbar for quick and daily access to your motivational quotes.

- **⏰ Automatic Quote Display**
  - Automatically display new quotes at user-defined intervals. Customize the frequency and enable or disable this feature in the settings panel.

- **📜 Random Motivational Quotes**
  - Click the extension icon to display a new, randomly selected motivational quote each time.

- **➡️ Next Quote Button**
  - Easily navigate to the next quote with a dedicated "Next" button for continuous inspiration.

- **⏳ Real-Time Age Display**
  - Toggle to display your current age in real-time, calculated to 8 decimal places based on your birth date.

- **🌗 Light & Dark Mode**
  - Switch between light and dark modes effortlessly to match your browsing preference.

---

## 🔧 How to Use

1. **📌 Pin the Extension**
   - Click the Chrome extensions menu (puzzle piece icon) in the toolbar.
   - Find **Motivation Tool Daily Quotes** and click the pin icon to keep it visible on your toolbar.

2. **💡 Display a New Quote**
   - Click the pinned extension icon daily to view a fresh inspirational quote and stay motivated.

3. **⏰ Set Automatic Quote Intervals**
   - Open the extension settings to enable automatic quote display.
   - Adjust the interval (in minutes) and auto close delay (in seconds) to suit your preferences.

4. **📅 Enter Your Birth Date**
   - Open the extension settings and input your birth date to see your age update in real-time, calculated to 8 decimal places.

5. **🌙 Toggle Display Modes**
   - Use the toggle switch within the extension to switch between light and dark modes based on your preference.

6. **➡️ Navigate Through Quotes**
   - Click the "Next" button to browse through additional motivational quotes whenever you need a boost.

---

## 🚀 What’s New

### **Version 1.2.1 - 1.2.1.5**

1. **Automatic Quote Display**
   - Stay inspired without lifting a finger! New quotes can now appear automatically at intervals you set.
   - **Customizable Popup Intervals:** Adjust the frequency and delay of automatic quotes to fit your schedule and preferences.
   - **Bug Fix:** Resolved an issue that allowed multiple popup windows to open simultaneously, ensuring a consistent user experience.

2. **Control Popup Mechanism**
   - Enable or disable the automatic quote display directly from the settings panel for greater flexibility.

3. **Expanded Quote Library**
   - Added new quotes from Vincent van Gogh, Sumerian, Ur, Babylonian, Assyrian Proverbs, Salvador Dali, Rumi, and more.
     - *Example:* "At the age of six I wanted to be a cook. At seven I wanted to be Napoleon. And my ambition has been growing steadily ever since." - Salvador Dali
     - *Example:* "No one is tall enough to reach up and touch the heavens. No one is broad enough to lift his gaze over the whole earth. [...] But you, who roar like a storm -- may you establish yourself like a lion. [...] No man can bring about your demise." - Sumerian Proverbs
     - *Example:* "Let the beauty of what you love be what you do." - Rumi
     - *Example:* "Great things are done by a series of small things brought together." - Vincent van Gogh"

---

## 🔮 Coming Soon

- **🔔 Non-Intrusive Notifications**
  - Enhancing the automatic quote display to be even less disruptive to your workflow, ensuring motivation without interruption.

---

## 💻 Tech Stack

The **Motivation Tool** Chrome extension is built using a robust and modern technology stack to ensure a seamless and efficient user experience.

- **🔧 Languages & Frameworks:**
  - **TypeScript:** Provides static typing for JavaScript, enhancing code quality and maintainability.
  - **React:** A powerful JavaScript library for building user interfaces, enabling dynamic and responsive components.
  - **Styled-Components:** Utilized for writing CSS in JavaScript, allowing for scoped and maintainable styles.

- **📦 Package Management:**
  - **npm:** Manages project dependencies and scripts.

- **🔧 Build Tools:**
  - **CRACO (Create React App Configuration Override):** Allows customization of the Create React App configuration without ejecting.
  - **Webpack:** Bundles JavaScript files for browser usage.

- **🔒 Storage & APIs:**
  - **Chrome Storage API:** Manages user settings and preferences, ensuring data persistence across sessions.
  - **Chrome Alarms API:** Schedules and manages the timing of popup displays.

- **🛠 Development Tools:**
  - **ESLint:** Ensures code quality and consistency.
  - **Prettier:** Formats code for readability and maintainability.
  - **Jest & React Testing Library:** Provides a robust testing environment for unit and integration tests.

- **🌐 Deployment:**
  - **Chrome Web Store:** Distributes the extension to millions of users worldwide.

---

## 📂 Project Structure gist

```
motivation-tool-daily-quotes/
├── public/
│   ├── popup.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── Settings.tsx
│   │   ├── Popup.tsx
│   │   └── ...
│   ├── styles/
│   │   ├── GlobalStyles.ts
│   │   ├── Theme.ts
│   │   └── ...
│   ├── quotes.json
│   ├── background.ts
│   ├── App.tsx
│   └── ...
├── package.json
├── tsconfig.json
├── README.md
└── ...
```

---

## 🙌 Contact & Contributing

Contributions are welcome! If you'd like to contribute or you have question, feedback or idea for to the Motivation Tool, please contact me via email: marczynski(dot)tomasz at gmail.com

---


**Stay motivated and inspired every day with Motivation Tool Daily Quotes!** Pin the extension now and make daily inspiration a seamless part of your browsing experience.
