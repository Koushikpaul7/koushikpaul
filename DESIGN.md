---
name: Terminal Emerald Portfolio
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#45dfa4'
  on-tertiary: '#003825'
  tertiary-container: '#00b982'
  on-tertiary-container: '#00422c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#68fcbf'
  tertiary-fixed-dim: '#45dfa4'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
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

This design system embodies a battle-tested, high-craft developer persona. It merges retro computing nostalgia (CLI interfaces, monospaced data readouts, status beacons) with contemporary ultra-refined SaaS design (frosted glass layers, subtle ambient emerald glows, and crisp geometric typographic hierarchy). 

The target audience encompasses engineering leaders, global recruiters, and technical peers seeking rock-solid engineering competency, obsessive attention to detail, and modern product sensibilities. The interface evokes quiet authority, deep technical focus, and precision.

## Colors

The palette leverages an obsidian deep-slate canvas paired with high-energy radiant emeralds and technical cyan-teal undertones:

- **Canvas & Surface Base:** Deepest Slate (`#0B0F19`) for the root canvas, transitioning to Slate 900 (`#0F172A`) and translucent Slate 900 (`rgba(15, 23, 42, 0.60)`) for card containers.
- **Primary Accent:** Glowing Emerald (`#10B981`) drives primary interactive elements, active status indicators, and focus rings. 
- **Secondary & Tertiary:** Cool Cyan (`#06B6D4`) and Mint Emerald (`#34D399`) serve as terminal output highlights, syntax tokens, and secondary tag accents.
- **Borders & Dividers:** Subtle, low-noise slate strokes (`rgba(30, 41, 59, 0.80)`) maintain visual structure without competing with foreground copy.
- **Typography Tones:** High-contrast White (`#F8FAFC`) for headings, Slate 300 (`#CBD5E1`) for body text, and Slate 500 (`#64748B`) for structural metadata.

## Typography

Typography establishes an intentional dialectic between technical precision and human-centric clarity:

- **Display & Headlines:** Plus Jakarta Sans provides clean, contemporary geometry with tightened letter tracking and confident weights (600–800) for hero hooks and section anchors.
- **Body & Editorial:** Inter delivers neutral, hyper-legible rendering across high pixel densities, calibrated with generous line heights to preserve reading comfort on dark backdrops.
- **Terminal & Metadata:** JetBrains Mono is strictly enforced for status pills, shell commands, timestamp ribbons, and technical taxonomy tags.

## Layout & Spacing

The layout follows a modular 12-column grid system capped at a maximum width of `1280px` for desktop viewports, downshifting to a 4-column fluid structure on mobile devices (`< 768px`). 

Vertical rhythm is governed strictly by an 8px scale. Spacing tokens ensure visual breathing room around dense terminal components while preserving tight internal groupings between command prompts, badges, and contextual metadata.

## Elevation & Depth

Visual depth is achieved through layered translucency and subtle colored luminescence rather than heavy black drop shadows:

- **Canvas:** Raw `#0B0F19` void with optional radial emerald spotlight gradients (`radial-gradient(circle at 50% 0%, rgba(16, 185, 129, 0.08), transparent 70%)`).
- **Glassmorphism Panels:** `background: rgba(15, 23, 42, 0.60)`, conditioned with `backdrop-filter: blur(12px)` and a sharp hair-line perimeter `1px solid rgba(30, 41, 59, 0.80)`.
- **Active Glows:** Interactive and featured modules receive an ambient emerald halo: `box-shadow: 0 0 30px -10px rgba(16, 185, 129, 0.25)`.

## Shapes

The interface adopts a balanced `roundedness: 2` scale. Standard cards and containers use an outer corner radius of `0.5rem` (8px), scaling to `1rem` (16px) for large hero feature panels (`rounded-lg`). Small controls, technical badges, and terminal windows use `0.375rem` to `0.5rem` to retain an architectural, modern software tool finish without feeling bulbous.

## Components

### Buttons
- **Primary:** Solid `#10B981` fill with `#0B0F19` bold typography. Hover states introduce an upward 1px transform and an outer emerald wash (`box-shadow: 0 0 20px rgba(16, 185, 129, 0.4)`).
- **Secondary / Ghost:** Translucent Slate 800 background (`rgba(30, 41, 59, 0.5)`) with a `1px solid rgba(16, 185, 129, 0.3)` boundary and JetBrains Mono text.

### Interactive Terminal Card
- **Frame:** Window header with three minimalist dot controls (`#EF4444`, `#F59E0B`, `#10B981` at 8px diameter), followed by monospaced user path title (`koushik@dhaka-node:~`).
- **Body:** JetBrains Mono content with green `$` prompt indicators, cyan execution commands, and slate response output.

### Status Pills & Technical Chips
- **Availability Pill:** Emerald dot with an active CSS radar pulse animation (`ping`), accompanied by uppercase text reading `AVAILABLE FOR GLOBAL ROLES`.
- **Skill Badges:** JetBrains Mono pill badges featuring dark slate surfaces, subtle 1px slate-800 borders, and muted green/cyan text.

### Timeline Cards
- **Structure:** Vertical connecting spine using a faint emerald gradient (`from-emerald-500/40 to-transparent`). 
- **Milestone Nodes:** Glassmorphic content cards offset with monospaced company/date anchors and clear impact bulleting.