# Specification Document: Minimalist Futuristic Landing Page

## Role
Senior Frontend Developer with an expert eye for UI/UX, micro-interactions, and modern responsive design.

## Technical Constraints & Stack
- **Architecture**: Semantic HTML5, Mobile-First approach.
- **Styling**: Tailwind CSS (CDN/JIT via Utility Classes) + custom CSS variables for theme switching. BEM methodology reserved strictly for complex custom components if required.
- **Frameworks**: Plain HTML & CSS only (vanilla JS strictly allowed only for the theme toggle state switch).
- **Output**: Single-file HTML snippet or structure.

## Design System & Theme Config

### Color Palette (Tailwind Tokens)
- `--color-bg-primary`: `#F5F5F5` (Light) / `#282C34` (Dark)
- `--color-text-primary`: `#282C34` (Light) / `#F5F5F5` (Dark)
- `--color-accent`: `#61DAFB` (Accent / Glow effects)
- `--color-surface`: `#FFFFFF` (Light) / `#4B4C54` (Dark)

### Aesthetics
- **Style**: Minimalist Futuristic.
- **Visual Features**: Clean typography, subtle glassmorphism (`backdrop-blur`), thin borders, and soft glow effects on hover.

---

## Page Structure & Component Specs

### 1. Header (`<header>`)
- **Layout**: Fixed/Sticky top navigation with `backdrop-blur-md` and `z-50`.
- **Left**: Logo mark with minimalist vector/SVG or typography.
- **Right**:
  - Navigation links (`About Us`, `Work With Us`, `Samples`) with animated hover underlines using `transition-all`.
  - **Theme Switcher**: Day/Night toggle button using standard HTML `<button>` switching a `.dark` class on the `<html>` element.

### 2. Hero Section (`<section id="hero">`)
- **Dimensions**: `min-h-screen` (100vh) flexbox/grid layout centered.
- **Content**: Bold headline conveying company values with high-contrast typography and dynamic accent accents.
- **Visual**: Inline minimalist SVG vector (futuristic abstract geometry or wireframe illustration).

### 3. Product / Portfolio Section (`<section id="samples">`)
- **Layout**: Responsive Tailwind Grid (`grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8`).
- **Cards**:
  - Glassmorphic card design (`bg-surface`, thin border `#4B4C54/20`, subtle hover translate/glow).
  - High-fidelity mockups representing client websites.
  - Minimal details (Title, Tag, View Project CTA).

### 4. Footer (`<footer>`)
- **Layout**: Split section on desktop (`flex-col md:flex-row justify-between`).
- **Content Left**: Legal disclaimers, copyright notice ("All rights reserved").
- **Content Right**: Contact channels (email, social links) with subtle hover feedback.