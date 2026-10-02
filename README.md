# Wild Sage Journey — Health & Wellness Coaching Landing Page

An editorial, cinematic single-page website prototype for **Wild Sage Journey** (guided by Beth Eberle, B.S., CHWC), designed to support women in rebuilding self-trust, sovereignty, and radiance after life transitions and divorce.

Inspired by the patient-luxury **Olosirkon** editorial design system.

## 🌿 Aesthetic & Design System

- **Palette**:
  - `Gold (#C8A24B)` — Voltage accent, glow theme, hairlines & primary CTAs.
  - `Bone (#EFE8DC / #F7F3EB)` — Tactile, high-end editorial canvas.
  - `Charcoal (#22201C / #181613)` — Deep grounding ink & full-bleed dark panels.
  - `Ochre (#B05A2E)` — Sparing secondary accent (dropcap & sequence eyebrows).
  - `Acacia (#5C6B4A)` — Sparing organic accent (marginal notes & callouts).
- **Typography**:
  - `Fraunces` — Light serif display for headings and pull-quotes.
  - `Lora` — Body copy.
  - `Archivo` — All-caps kickers, timestamps, and specs (`letter-spacing: 0.22em`).
- **Geometry**: Strictly flat and rectangular with 1px hairline rules and no drop shadows.

## 🛠️ Tech Stack & Structure

- Pure semantic HTML5 + Vanilla CSS + Google Fonts
- Fully responsive across desktop, tablet, and mobile
- Integrated booking consultation modal
- Explicit `id` and `data-testid` attributes for Playwright / E2E automated testability

## 🚀 Running Locally

Open `index.html` directly in your browser, or start a local static server:

```bash
# Using Python
python -m http.server 8080

# Or using npx serve
npx serve .
```
