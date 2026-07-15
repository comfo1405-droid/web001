## Overview

Vishfolio is a modern developer portfolio focused on:
- cinematic layouts
- subtle interaction
- glassmorphism
- motion-driven UI
- premium typography
- responsive frontend systems

Built for developers who want a clean and visually polished digital identity.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js App Router | Framework |
| TypeScript | Type safety |
| Tailwind CSS | Styling |
| Framer Motion | Motion system |
| GSAP | Advanced animations |
| React Three Fiber | 3D rendering |
| Drei | R3F helpers |
| Lenis | Smooth scrolling |

---

## Features

- Smooth scrolling experience
- Interactive project cards
- Motion-based UI transitions
- Responsive layout system
- Premium dark visual design
- Floating interaction elements
- Glassmorphism surfaces
- 3D hero atmosphere
- Clean developer-focused structure

---

## Screenshots


<p align="center">
  <img src="https://i.imgur.com/UqTikWD.png" width="92%" />
</p>

<p align="center">
  <img src="https://i.imgur.com/plRQoSs.png" width="92%" />
</p>


---

# Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/vishfolio.git
```

Move into the project directory:

```bash
cd vishfolio
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open:

```txt
http://localhost:3000
```

---

# Project Structure

```bash
app/
 ├── globals.css
 ├── layout.tsx
 └── page.tsx


```

---

# Customization Guide

This project is intentionally easy to edit and personalize.

## Edit Personal Information

Open:

```txt
app/page.tsx
```

Change:
- hero heading
- description
- contact links
- technologies
- project cards
- section content

---

## Change Theme / Colors

Open:

```txt
app/globals.css
```

Main variables:

```css
:root {
  --background: #050607;
  --foreground: #eef5f8;
  --cyan-soft: rgba(125, 227, 255, 0.18);
}
```

You can fully re-theme the portfolio here.

---

## Remove the 3D Orb Scene

Inside:

```txt
app/page.tsx
```

Remove:

```tsx
<Scene />
```

This disables:
- the floating orb
- cinematic glow
- 3D background atmosphere

You can also remove:

```tsx
<FloatingTech />
```

for a cleaner minimal layout.

---

## Edit Projects

Inside:

```tsx
const projects = [...]
```

Update:
- titles
- descriptions
- stacks
- gradients

---

## Edit Technologies

Inside:

```tsx
const technologies = [...]
```

These control the floating tech pills around the hero section.

---

## Motion & Animation

Animation systems use:
- Framer Motion
- GSAP
- Lenis

Main animation logic lives in:

```txt
app/page.tsx
```

Search for:
- `motion.div`
- `gsap`
- `useMotionValue`
- `whileHover`

---

## Replace Screenshots

Add your own images inside:

```txt
public/
```

Recommended:
- `preview.png`
- `hero.png`
- `projects.png`

---

# Design Direction

Inspired by:
- Linear
- Vercel
- Framer
- Apple developer pages
- Modern cinematic UI systems

Focused on restraint, spacing, depth, and smooth interaction.

---

# Deployment

Deploy instantly on:

- Vercel
- Netlify
- Railway

---


Focused on crafting smooth developer experiences with modern frontend systems.

---

<p align="center">
  Designed with motion, clarity, and restraint.
</p>
