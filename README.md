# 🧊 LiquidGlass UI

A sleek open-source Apple-style "liquid glass" UI components library for modern web apps, built with **Next.js** and **Tailwind CSS**.

## ✨ Features

- Frosted glass UI components (blurred + translucent)
- 100% responsive & mobile-friendly
- Easy to customize with Tailwind CSS
- Built for Next.js + React
- MIT Licensed – Free for personal and commercial use

## 📦 Included Components

| Component       | Description                          |
|----------------|--------------------------------------|
| `GlassCard`     | Frosted container for content        |
| `GlassButton`   | Translucent rounded button           |
| `GlassInput`    | Blur input field                     |
| `GlassNavbar`   | Sticky translucent navbar            |
| `GlassModal`    | Animated modal with blur             |
| `GlassSidebar`  | Fixed blur sidebar navigation        |
| `GlassFooter`   | Minimal footer with blur             |
| `GlassTooltip`  | Hover tooltip with glass style       |
| `GlassBadge`    | Mini tag with blur                   |
| `GlassLoader`   | Spinning loader in blur style        |

## 🚀 Getting Started

1. **Install Tailwind CSS** in your Next.js project:  
   [Tailwind CSS Docs →](https://tailwindcss.com/docs/guides/nextjs)

2. **Copy Components**  
   Place the files inside the `/components` directory of your project.

3. **Use a Component**

```tsx
import { GlassCard, GlassButton } from "@/components/GlassCard";

export default function Home() {
  return (
    <GlassCard>
      <h1 className="text-white text-xl font-bold">Welcome to LiquidGlass</h1>
      <GlassButton label="Click Me" onClick={() => alert("Hello!" )} />
    </GlassCard>
  );
}
