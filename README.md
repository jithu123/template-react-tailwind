# template-react-tailwind

## 🚀 1. Create the App
cd template-react-tailwind
pnpm install
pnpm dev

Here's a **starter template** with:

* ✅ **Vite**
* ✅ **React + TypeScript**
* ✅ **Tailwind CSS**

---

## 🚀 1. Create the App

```bash
pnpm create vite my-app --template react-ts
cd my-app
pnpm install
```

---

## 🎨 2. Install Tailwind CSS

```bash
pnpm add -D tailwindcss postcss autoprefixer
pnpm dlx tailwindcss init -p
```

---

## ⚙️ 3. Configure Tailwind

Update `tailwind.config.js`:

```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

Replace everything in `src/index.css` with:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 💻 4. Edit Your App

Update `src/App.tsx`:

```tsx
function App() {
  return (
    <div className="min-h-screen flex items-center justify-center bg-gradient-to-r from-indigo-500 to-purple-500 text-white text-3xl font-bold">
      🚀 Hello Vite + React + Tailwind!
    </div>
  );
}

export default App;
```

---

## ▶️ 5. Run Your App

```bash
pnpm dev
```

Then open [http://localhost:5173](http://localhost:5173)

---

## 📁 Folder Structure Overview

```
my-app/
├── index.html
├── tailwind.config.js
├── postcss.config.js
├── src/
│   ├── App.tsx         // Your main component
│   ├── main.tsx        // Entry point
│   └── index.css       // Tailwind CSS here
├── package.json
└── ...
```

---


