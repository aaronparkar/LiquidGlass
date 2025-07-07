```markdown
# 🧊 LiquidGlass UI

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)  
✨ 30+ Apple-style **frosted glass** UI components built using **Next.js**, **TypeScript**, and **Tailwind CSS**.

---

## 🎬 Live Demo

> Coming soon — or host it yourself locally!

```bash
npm run dev
```

---

## 🖼️ Preview

![LiquidGlass UI Preview](https://user-images.githubusercontent.com/your-image-placeholder.png)

---

## ✨ Features

- 🧱 30 modular, reusable `.tsx` components  
- 🌈 Glassmorphism: blur, transparency, reflections  
- 📱 Fully responsive and mobile-ready  
- 🎨 Styled with TailwindCSS utility classes  
- 🌙 Dark mode friendly (customizable)  
- ⚡ Powered by React (with Framer Motion support)  
- 🧩 Easy to extend, wrap, or theme  
- 📦 MIT Licensed — no restrictions  

---

## 📦 Component Catalog

### 📌 Base Elements
- `GlassCard`
- `GlassButton`
- `GlassInput`
- `GlassNavbar`
- `GlassSidebar`
- `GlassModal`
- `GlassTooltip`
- `GlassBadge`
- `GlassLoader`
- `GlassFooter`

### 📚 UI Elements
- `GlassDropdown`
- `GlassSelect`
- `GlassToast`
- `GlassTabs`
- `GlassAccordion`
- `GlassBreadcrumb`
- `GlassSwitch`
- `GlassCheckbox`
- `GlassRadio`

### 📊 Data/Visual
- `GlassChartContainer`
- `GlassProgressBar`
- `GlassStatsCard`
- `GlassCalendar`
- `GlassNotificationCard`

### 🚀 Layout & Advanced
- `GlassHero`
- `GlassWidgetBox`
- `GlassTimeline`
- `GlassScrollPanel`
- `GlassFormWrapper`
- `GlassAvatar`

---

## 🚀 Getting Started

### 1. Install Tailwind CSS

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 2. Configure TailwindCSS

```js
// tailwind.config.js
module.exports = {
  content: [
    "./app/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}"
  ],
  theme: {
    extend: {
      dropShadow: {
        glass: "0 4px 30px rgba(0, 0, 0, 0.1)",
      },
      colors: {
        glassWhite: "rgba(255, 255, 255, 0.25)",
      },
      backdropBlur: {
        xs: '2px',
        lg: '12px',
      }
    },
  },
  plugins: [],
};
```

### 3. Use Global Styles (e.g. in `globals.css`)

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

---

## 🧪 Example Usage

```tsx
import { GlassCard } from "@/components/GlassCard";
import { GlassButton } from "@/components/GlassButton";

export default function Home() {
  return (
    <main className="min-h-screen bg-neutral-900 p-8">
      <GlassCard>
        <h1 className="text-white text-2xl font-bold mb-4">Welcome to LiquidGlass UI</h1>
        <GlassButton label="Click Me" onClick={() => alert("Hello!")} />
      </GlassCard>
    </main>
  );
}
```

---

## 🎞️ Optional: Enable Animations

Want animated modals, dropdowns, or loaders? Use `framer-motion`.

### Install:
```bash
npm install framer-motion
```

### Use:
```tsx
import { motion } from "framer-motion";

<motion.div
  initial={{ opacity: 0, scale: 0.9 }}
  animate={{ opacity: 1, scale: 1 }}
  exit={{ opacity: 0, scale: 0.95 }}
  transition={{ duration: 0.2 }}
>
  {/* Your glass component */}
</motion.div>
```

---

## 🛠️ Roadmap Ideas

- [ ] Add theme switch (dark/light toggle)  
- [ ] Create Live CodeSandbox integration  
- [ ] Publish as `npm` package  
- [ ] Add mobile-first layout kit  

---

## 🤝 Contributing

We welcome all kinds of contributions:
- 💡 Ideas
- 🐛 Bug fixes
- 🔧 Component improvements
- 📖 Docs

To contribute:
1. Fork the repo  
2. Clone it  
3. Add your feature branch  
4. Submit a pull request ✅

---

## 📄 License

**MIT License**  
Free for personal and commercial use. No attribution required.

---

Made with ❤️ by **Ansh Bhardwaj**
```
