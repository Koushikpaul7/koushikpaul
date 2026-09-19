---
name: Electric Blue & Slate (GitHub Dark Pro)
colors:
  surface: '#0d1117'
  surface-dim: '#090d13'
  surface-bright: '#161b22'
  surface-container-lowest: '#04070b'
  surface-container-low: '#0d1117'
  surface-container: '#161b22'
  surface-container-high: '#21262d'
  surface-container-highest: '#30363d'
  on-surface: '#f0f6fc'
  on-surface-variant: '#8b949e'
  inverse-surface: '#f0f6fc'
  inverse-on-surface: '#0d1117'
  outline: '#30363d'
  outline-variant: '#21262d'
  surface-tint: '#58a6ff'
  primary: '#58a6ff'
  on-primary: '#040d21'
  primary-container: '#1f6feb'
  on-primary-container: '#f0f6fc'
  inverse-primary: '#388bfd'
  secondary: '#38bdf8'
  on-secondary: '#082f49'
  secondary-container: '#0284c7'
  on-secondary-container: '#f0f9ff'
  tertiary: '#79c0ff'
  on-tertiary: '#041022'
  tertiary-container: '#1158c7'
  on-tertiary-container: '#e6f0ff'
  error: '#f85149'
  on-error: '#490202'
  error-container: '#da3633'
  on-error-container: '#ffdcd7'
  background: '#0d1117'
  on-background: '#f0f6fc'
  surface-variant: '#161b22'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1.5'
    letterSpacing: -0.01em
  label-badge:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system embodies a disciplined, modern developer persona based on the **GitHub Dark Pro & Electric Slate** aesthetic. It unites developer ergonomics (CLI terminal, monospaced metrics, clean status indicators) with refined SaaS aesthetics (frosted glass layers, subtle ambient electric blue halos, and crisp geometric typographic hierarchy).

The interface conveys authority, focus, and engineering rigor without excessive multi-color visual noise.

## Colors

The palette adheres to a disciplined **60-30-10 color balance**:

- **Canvas & Surface Base (60%):** Deepest Obsidian Canvas (`#0D1117`) transitioning to Slate Glass (`#161B22` / `rgba(22, 27, 34, 0.75)`).
- **Typography & Structure (30%):** High-contrast White (`#F0F6FC`) for headings, Slate 300 (`#CBD5E1`) for body text, and Slate 700 (`#30363D`) for hairline structural strokes.
- **Primary Signature Accent (10%):** Electric Sky Blue (`#58A6FF` / `#38BDF8`) powers CTAs, focus outlines, progress bars, and active states.
- **Single Semantic Indicator:** Emerald Green (`#10B981`) is reserved exclusively for the live "Available for Hire" status beacon and "All Systems Live" indicator.
- **Borders & Dividers:** Subtle slate strokes (`rgba(48, 54, 61, 0.80)`) preserve structure cleanly.

## Typography

- **Display & Headlines:** Plus Jakarta Sans with bold weights (700–800) and tightened tracking (`-0.02em`) rendered in radiant white and soft sky gradient accents.
- **Body & Explanatory:** Inter with balanced line heights (1.6) in neutral slate ensuring fatigue-free reading.
- **Terminal & Monospace Data:** JetBrains Mono for shell commands, timestamps, version numbers, metrics, and pill tags.

## Components

### Buttons
- **Primary:** Gradient `#2563EB` to `#0EA5E9` fill (`from-blue-600 to-sky-500`) with `#020617` bold typography and electric blue glow on hover.
- **Secondary / Ghost:** Glassmorphic Slate 900 background with a `1px solid rgba(88, 166, 255, 0.3)` boundary.

### Interactive Terminal Card
- **Window Frame:** Standard window dots (`#EF4444`, `#F59E0B`, `#10B981`), with clean slate header and terminal prompt.
- **Prompt:** Crisp `$` indicator with electric blue command highlights.

### Skills & Progress Indicators
- **Filter Pills:** Active filter button in solid electric blue (`bg-blue-500 text-slate-950 font-bold`), inactive pills in dark slate glass.
- **Progress Trackers:** Cohesive electric blue-to-sky gradient (`from-blue-600 to-sky-400`).

### Status Beacon
- **Live Status:** Emerald ping ring (`#10B981` / `bg-green-400 animate-ping`) indicating active worldwide availability.