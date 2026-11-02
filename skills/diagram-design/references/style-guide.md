<!-- diagram-design-profile
name: Architecture Diagram Light
slug: architecture-diagram-light
source-url: none
created: 2026-11-01
updated: 2026-11-01
notes: Extracted from architecture-diagram skill (Slate / Cyan palette)
-->
# Style Guide

Extracted from installed skill `architecture-diagram`. Crisp slate background with cyan accent.

## Tokens

### Semantic roles

| Role | Purpose | Default (light) | Default (dark) |
|---|---|---|---|
| `paper` | Page background, default node fill | `#f8fafc` (slate-50) | `#0f172a` (slate-900) |
| `paper-2` | Diagram container bg, secondary fill | `#ffffff` | `#1e293b` |
| `ink` | Primary text, primary stroke | `#0f172a` (slate-900) | `#f8fafc` (slate-50) |
| `ink-strong` | High-contrast text on warm accent fills | `#ffffff` | `#ffffff` |
| `muted` | Secondary text, default arrow stroke | `#475569` (slate-600) | `#94a3b8` (slate-400) |
| `soft` | Sublabels, boundary labels | `#64748b` (slate-500) | `#cbd5e1` (slate-300) |
| `rule` | Hairline borders | `rgba(15,23,42,0.12)` | `rgba(248,250,252,0.12)` |
| `rule-solid` | Stronger borders, baselines | `#cbd5e1` (slate-300) | `rgba(148,163,184,0.30)` |
| `accent` | Focal / 1–2 max per diagram | `#0e7490` (cyan-700) | `#38bdf8` (sky-400) |
| `accent-tint` | Fill for accent-bordered boxes | `rgba(14,116,144,0.08)` | `rgba(56,189,248,0.12)` |
| `link` | HTTP/API calls, external arrows | `#0284c7` (sky-600) | `#38bdf8` (sky-400) |

## Typography

| Role | Family | Size | Weight | Usage |
|---|---|---|---|---|
| `title` | Instrument Serif | 1.75rem | 400 | Page H1 |
| `node-name` | Geist (sans) | 12px | 600 | Human-readable labels |
| `sublabel` | JetBrains Mono | 9px | 400 | Port, protocol, URL, field type |
| `eyebrow` | JetBrains Mono | 7–8px | 500, tracked 0.18em, uppercase | Type tags, axis labels |
| `arrow-label` | JetBrains Mono | 8px | 400, tracked 0.06em | Arrow annotations |
| `callout` | Instrument Serif *italic* | 14px | 400 | Editorial asides only |
