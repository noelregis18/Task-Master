# TaskMaster

A modern, minimal, and beautiful Todo app built with **React**, **TypeScript**, **Vite**, and **Tailwind CSS**.

Organize your tasks and notes in one place. Easily add, edit, complete, and delete tasks, with support for categories and notes.

---

## Features

- Add, edit, and delete tasks
- Mark tasks as completed or active
- Add notes and categorize tasks (Personal, Work, Shopping, Other)
- Filter tasks by status and category
- Responsive, clean, and accessible UI
- Built with React Context for state management
- Powered by Vite for fast development
- Styled with Tailwind CSS

---

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd <project-folder>
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Start the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## Project Structure

```
Project 69/
├── src/
│   ├── components/      # TodoForm, TodoList components
│   ├── context/         # TodoContext for state management
│   ├── types.ts         # TypeScript types
│   ├── App.tsx          # Main app component
│   └── main.tsx         # Entry point
├── index.html           # HTML entry
├── tailwind.config.js   # Tailwind CSS config
├── postcss.config.js    # PostCSS config
├── package.json         # Project metadata and scripts
└── ...
```

---

## Scripts

- `npm run dev` — Start development server
- `npm run build` — Build for production
- `npm run preview` — Preview production build
- `npm run lint` — Lint code with ESLint

---

## Customization
- **Categories:** Easily add or modify categories in `TodoForm.tsx` and `TodoList.tsx`.
- **Styling:** Customize Tailwind config in `tailwind.config.js`.

---

## License

MIT

---

## Credits

Developed by Noel Regis 
