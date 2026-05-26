# 🎮 Tic-Tac-Toe

A clean, responsive **Tic-Tac-Toe** game built with **React** and **Vite**, styled using **Tailwind CSS** — and deployed live on Vercel.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?style=for-the-badge&logo=vercel)](https://tic-tac-toe-blush-nu-38.vercel.app)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)

---

## 📸 Preview

> Play it live → [tic-tac-toe-blush-nu-38.vercel.app](https://tic-tac-toe-blush-nu-38.vercel.app)

---

## ✨ Features

- ♟️ **Two-player** local gameplay (X vs O)
- ✅ **Win detection** across all rows, columns, and diagonals
- 🤝 **Draw detection** when the board is full
- 🔄 **Restart / Reset** button to start a new game
- 📱 **Fully responsive** — plays great on mobile and desktop
- ⚡ **Blazing fast** dev experience with Vite HMR

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React](https://react.dev) | UI component library |
| [Vite](https://vitejs.dev) | Build tool & dev server |
| [Tailwind CSS](https://tailwindcss.com) | Utility-first styling |
| [ESLint](https://eslint.org) | Code linting |
| [Vercel](https://vercel.com) | Deployment & hosting |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Riddhi73/tic-tac-toe.git

# 2. Navigate into the project directory
cd tic-tac-toe

# 3. Install dependencies
npm install
```

### Running Locally

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to play.

### Building for Production

```bash
npm run build
```

The optimized output will be in the `dist/` folder.

### Preview the Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
tic-tac-toe/
├── public/             # Static assets
├── src/                # React source code
│   ├── components/     # Game components (Board, Square, etc.)
│   ├── App.jsx         # Root application component
│   └── main.jsx        # Entry point
├── index.html          # HTML template
├── tailwind.config.js  # Tailwind CSS configuration
├── vite.config.js      # Vite configuration
├── eslint.config.js    # ESLint configuration
└── package.json        # Project metadata & dependencies
```

---

## 🎯 How to Play

1. The game starts with **Player X**.
2. Players take turns clicking empty squares to place their mark.
3. The first player to get **3 in a row** (horizontally, vertically, or diagonally) wins.
4. If all 9 squares are filled with no winner, the game ends in a **draw**.
5. Click **Restart** to play again.

---

## 🌐 Deployment

This project is deployed on **Vercel**. Any push to the `master` branch will automatically trigger a new deployment.

To deploy your own fork:

1. Import the repo into [Vercel](https://vercel.com/new)
2. Set the framework preset to **Vite**
3. Click **Deploy** — done!

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the project
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature"

# 4. Push to the branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Riddhi73**  
GitHub: [@Riddhi73](https://github.com/Riddhi73)

---

<p align="center">Made with ❤️ using React & Vite</p>
