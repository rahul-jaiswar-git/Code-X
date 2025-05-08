# Code-X: Online Code Editor

![GitHub repo size](https://img.shields.io/github/repo-size/rahul-jaiswar-git/Code-X?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/rahul-jaiswar-git/Code-X?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/rahul-jaiswar-git/Code-X?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/rahul-jaiswar-git/Code-X?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/rahul-jaiswar-git/Code-X?style=for-the-badge)

![Project Home Page](./screenshots/img.png)

> Code-X is a web-based code editor supporting multiple languages, syntax highlighting, theming, and code execution via a cloud backend. It is built with React, Ace Editor, and Material UI, and is designed for fast, interactive coding directly in the browser.

## What is Code-X?

Code-X is an online code editor that allows users to write, run, and test code in various programming languages directly from their browser. It features a modern UI, language selection, theming, and the ability to copy or download code. Code execution is handled by a backend API, making it ideal for learning, quick prototyping, and demonstrations.

> **Note:**  
> The backend for code execution is hosted on a free Render instance and may experience cold starts. The app is currently optimized for desktop and may not be fully responsive on mobile devices.

### Key Features

- [x] Multi-language code editor (C, C++, Java, Python, Go, JavaScript)
- [x] Syntax highlighting and autocompletion (Ace Editor)
- [x] Input/output support for code execution
- [x] Download and copy code snippets
- [x] Multiple color themes (switchable)
- [x] Modern, responsive UI (Material UI)
- [x] Navigation between Home and Editor
- [ ] Mobile responsiveness (in progress)
- [ ] User authentication (planned)

## 💻 Prerequisites

- Node.js (v14 or higher)
- npm
- Git

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/rahul-jaiswar-git/Code-X.git
cd Code-X
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to:
```
http://localhost:5173/
```

## ☕ Usage

- Navigate to the Home page for an introduction.
- Click "Get Started" to open the Editor.
- Select your programming language from the dropdown.
- Write or paste your code in the editor.
- Provide custom input if needed.
- Click "Run" to execute your code (output appears on the right).
- Use the menu to copy or download your code.
- Switch themes using the color icons in the navbar.

## 🛠️ Technology Stack

- **Frontend**: React, Ace Editor, Material UI
- **Routing**: React Router
- **Theming**: Material UI custom themes
- **Code Execution Backend**: [Render-hosted API](https://code-box.onrender.com)
- **Build Tool**: Vite

## 🏗️ File Structure

```
Code-X/
├── public/                  # Static assets
│   └── favicon.png
├── screenshots/             # Screenshots for documentation
│   └── img.png              # Project Home Page image
├── src/
│   ├── assets/              # App images and icons
│   │   └── img.png
│   ├── components/          # React components
│   │   ├── Editor/
│   │   │   └── Editor.jsx   # Main code editor
│   │   ├── Home/
│   │   │   └── Home.jsx     # Home/landing page
│   │   └── Navbar/
│   │       └── Navbar.jsx   # Navigation bar
│   ├── utils/               # Utility modules
│   │   ├── cutomTheme.jsx   # Theme definitions
│   │   └── customContext.js # Context for theming
│   ├── App.jsx              # Main app component
│   ├── index.css            # Global styles
│   ├── main.jsx             # App entry point
├── .eslintrc.cjs            # ESLint config
├── index.html               # HTML entry point
├── package.json             # Project dependencies and scripts
├── package-lock.json        # Dependency lock file
├── README.md                # Project documentation
└── vite.config.js           # Vite config
```

## 🤝 Contributors

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/rahul-jaiswar-git" title="Rahul Jaiswar">
        <img src="https://avatars.githubusercontent.com/rahul-jaiswar-git" width="100px;" alt="Rahul Jaiswar's GitHub photo"/><br>
        <sub>
          <b>Rahul Jaiswar</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 