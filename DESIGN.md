---
name: George Shaheen Hyper-Minimal Portfolio
description: Hyper-minimal, understated single-mode personal portfolio and project showcase on ultra light grey
colors:
  bg: "#f4f4f5"
  text-primary: "#111827"
  text-muted: "#52525b"
  link: "#09090b"
  link-hover: "#1d4ed8"
  blue-dot: "#2563eb"
  border: "rgba(0, 0, 0, 0.08)"
typography:
  root:
    fontSize: "16px"
  display:
    fontFamily: "Sora, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
    fontSize: "1.85rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Sora, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.015em"
  body:
    fontFamily: "Sora, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "normal"
  mono:
    fontFamily: "JetBrains Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  mono-sm:
    fontFamily: "JetBrains Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "0.825rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  mono-xs:
    fontFamily: "JetBrains Mono, SFMono-Regular, Menlo, Consolas, monospace"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
spacing:
  sm: "0.85rem"
  md: "1.5rem"
  lg: "2.25rem"
  xl: "4rem"
  container: "9rem 2rem 10rem"
---

## Overview

A hyper-minimal, distraction-free personal portfolio for George Shaheen. Built on an ultra light grey background (`#f4f4f5`) with stark editorial restraint: no marketing fluff, no self-aggrandizing manifestos, no dark/light mode toggles, and no cards inside cards. Just name, essential links, and super clean project links with succinct descriptions.

## Colors

- **Ultra Light Grey Ground**: Single mode `#f4f4f5` (clean, calm, architectural paper feel).
- **Ink Primary**: Deep near-black `#111827` (16.2:1 contrast against ground).
- **Muted Neutral**: Crisp charcoal `#52525b` for project descriptions (7.1:1 contrast, well above WCAG AA).
- **Interactive Links**: Default muted hairline underline; on hover, shifts to a dotted redline (`#dc2626` / `#b91c1c`) with an animated traveling shimmer.

## Typography

- **Name / Heading**: `Sora` semi-bold (`1.85rem`, `-0.025em` tracking).
- **Project Titles**: `Sora` semi-bold (`1.15rem`, `-0.015em` tracking).
- **Descriptions**: `Sora` regular (`0.95rem`, line height 1.55).
- **Navigation & Actions**: `JetBrains Mono` (`0.875rem` / `0.825rem`).

## Layout

- Centered, narrow reading measure (`max-width: 580px`) with generous vertical whitespace (`6rem` mobile, `9rem` desktop).
- Clean vertical flow without containers, boxes, or side-tabs.

## Elevation & Depth

- Completely flat typographic hierarchy. Depth is created entirely through whitespace, font weight, and contrast.
- Zero shadows, zero borders on cards, zero artificial elevation.

## Shapes

- Native rectangular flow with zero decorative rounded containers.

## Components

- **Social Links**: Inline monospaced text links with subtle hairline underline decoration.
- **Project Items**: Simple title, concise one-line description, and monospaced action links (`live`, `site`, `source`).
- **Ambient Coordinate Canvas**: A quiet, low-contrast interactive coordinate field on `<canvas>` that gently deflects around pointer movement without demanding visual attention.

## Do's and Don'ts

### Do:
- Keep copy ruthlessly concise (one sentence per project).
- Preserve generous whitespace.
- Rely on typography, alignment, and spacing rather than cards or containers.

### Don't:
- Never add bio explanations, manifestos, or marketing jargon.
- Never add light/dark mode toggles; the site is intentionally single-mode ultra light grey.
- Never add borders, cards, or elevation boxes around projects.
