# 🤖 AI Code Explainer

An AI-powered web tool that explains any code in plain English — built with **React** and the **Claude API (Anthropic)**.

> Paste your code → Choose your level → Get an instant, clear explanation.

![AI Code Explainer](https://img.shields.io/badge/AI-Claude%20Sonnet-00e5ff?style=for-the-badge)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## ✨ Features

- 🌱 **3 Explanation Levels** — Beginner, Intermediate, Expert
- 🔤 **10+ Languages Supported** — JavaScript, Python, Java, C++, SQL, Go, Rust, and more
- ⚡ **Instant AI Explanation** — powered by Claude Sonnet (Anthropic)
- 📋 **Copy to Clipboard** — copy explanation with one click
- 🎨 **Clean Terminal UI** — dark hacker-themed interface
- 📱 **Responsive** — works on mobile and desktop

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | Frontend UI |
| Vite | Build tool |
| Claude API (Anthropic) | AI explanation engine |
| CSS-in-JS | Styling |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone (https://github.com/jatin8318/AI-Code-Explainer.git)
cd ai-code-explainer
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root folder:

```env
VITE_ANTHROPIC_API_KEY=your_api_key_here
```

> 🔑 Get your free API key at [console.anthropic.com](https://console.anthropic.com)

### 4. Run the App

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📁 Project Structure

```
ai-code-explainer/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx        # Main application component
│   └── main.jsx       # React entry point
├── .env               # API key (do NOT commit this)
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🧠 How It Works

1. User pastes code into the editor
2. Selects language and explanation level (Beginner / Intermediate / Expert)
3. Clicks **Explain This Code**
4. The app sends the code to Claude API with a custom prompt
5. Claude returns a structured explanation rendered in the UI

---

## 🎯 Use Cases

- 📚 Students learning to code
- 🧑‍💻 Developers understanding legacy code
- 🎓 Interview preparation
- 👨‍🏫 Teachers explaining code to students

---

## 📸 Screenshot

![AI Code Explainer Screenshot](assets/screenshot.png)(assets/screenshot(1).png)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**  
📧 your@email.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/YOUR_USERNAME)

---

> ⭐ If you found this useful, please star the repo!
