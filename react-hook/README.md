# ⚛️ React Hooks — Complete Reference

> A hands-on guide to mastering every React hook with practical, real-world examples and best practices.

---

## 📖 About This Project

This project is a structured, code-first exploration of **all React hooks** available in React 18+. Each hook lives in its own folder inside `src/hooks/`, making it easy to navigate, study, and experiment with individually.

Whether you're a beginner getting started with `useState` or diving deep into `useSyncExternalStore`, this repo has you covered.

---

## 🪝 Hooks Covered

| Hook | Purpose | Source |
| :--- | :--- | :---: |
| `useState` | Manage local component state and trigger re-renders on updates. | [View Code](./src/hooks/use-state/index.jsx) |
| `useEffect` | Run side effects like data fetching, subscriptions, and DOM updates. | [View Code](./src/hooks/use-effect/index.jsx) |
| `useContext` | Consume shared global state without prop drilling. | [View Code](./src/hooks/use-context/index.jsx) |
| `useReducer` | Handle complex state logic using a reducer function and dispatch pattern. | [View Code](./src/hooks/use-reducer/index.jsx) |
| `useRef` | Access DOM elements directly or persist mutable values across renders. | [View Code](./src/hooks/use-ref/index.jsx) |
| `useImperativeHandle` | Expose custom methods from a child component to its parent via `forwardRef`. | [View Code](./src/hooks/use-imperative-handle/index.jsx) |
| `useLayoutEffect` | Run synchronously after DOM mutations, before the browser paints. | [View Code](./src/hooks/use-layout-effect/index.jsx) |
| `useInsertionEffect` | Inject dynamic styles before layout effects fire — ideal for CSS-in-JS. | [View Code](./src/hooks/use-insertion-effect/index.jsx) |
| `useId` | Generate unique, stable IDs for accessibility and server-side rendering. | [View Code](./src/hooks/use-id/index.jsx) |
| `useTransition` | Keep the UI responsive by marking heavy state updates as non-urgent. | [View Code](./src/hooks/use-transition/index.jsx) |
| `useDeferredValue` | Defer re-rendering a non-critical value to improve perceived performance. | [View Code](./src/hooks/use-deferred-value/index.jsx) |
| `useSyncExternalStore` | Safely subscribe to and read from external data stores. | [View Code](./src/hooks/use-sync-external-store/index.jsx) |

---

## 🗂️ Project Structure

```
react-hook/
├── public/
│   └── vite.svg
├── src/
│   ├── App.jsx               # Root component and navigation
│   ├── App.css               # App-level styles
│   ├── main.jsx              # Application entry point
│   ├── index.css             # Global base styles
│   └── hooks/
│       ├── use-state/
│       ├── use-effect/
│       ├── use-context/
│       ├── use-reducer/
│       ├── use-ref/
│       ├── use-imperative-handle/
│       ├── use-layout-effect/
│       ├── use-insertion-effect/
│       ├── use-id/
│       ├── use-transition/
│       ├── use-deferred-value/
│       └── use-sync-external-store/
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm v9 or higher

### Installation & Running Locally

```bash
# 1. Navigate to the project folder
cd react-hook

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser. 🎉

---

## 🛠️ Tech Stack

| Tool | Purpose |
| :--- | :--- |
| [React 18](https://react.dev/) | UI library and hooks runtime |
| [Vite](https://vitejs.dev/) | Fast development server and bundler |
| [ESLint](https://eslint.org/) | Code quality and react-hooks rule enforcement |

---

## 🤝 Contributing

Found a bug or want to improve an example? Pull requests are welcome!

---

> Happy learning! Keep building, keep growing. 🌱
