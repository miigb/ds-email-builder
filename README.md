# DS Email Builder

Email template builder for **Letraperfeicoada / DS Credito** outreach campaigns. Pick a layout, choose a color scheme, copy the HTML, and paste into GoHighLevel or any email platform.

Built for the **Advogados (Lawyers) Outreach** campaign targeting law firms in Setubal.

---

## Features

**5 Layout Variants**

| Layout | Description |
|--------|-------------|
| Full Hero | Hero banner + 2x2 feature cards + stats row + dark CTA band + agent card |
| Compact | Accent bar header, inline feature rows, streamlined single CTA |
| Card First | Feature cards above the fold, body text below |
| Executive | Clean letter format, no cards or stats, single elegant CTA |
| Sidebar | Left accent stripe, integrated stats, compact agent signature |

**10 Color Schemes**

| Theme | Type | Accent |
|-------|------|--------|
| Original | Dark | Brand magenta from landing page |
| Brand Plum | Dark | Rich plum from brand guide |
| Slate & Teal | Dark | Professional teal |
| Warm Gold | Dark | Elegant gold from brand guide |
| Deep Navy | Dark | Authority blue |
| Light Rose | Light | Soft pink with magenta accents |
| Light Mint | Light | Fresh teal on white |
| Light Lavender | Light | Soft purple |
| Light Gold | Light | Warm cream with gold |
| Light Slate | Light | Minimal gray with brand accent |

**50 total combinations** (5 layouts x 10 themes)

---

## GoHighLevel Integration

The copied HTML includes GHL merge fields ready for campaign automation:

- `{{contact.name}}` auto-fills the recipient name from your leads list
- All CTAs link to `meuintermediario.com/#contact`
- Company details (Letraperfeicoada, BdP registration) are pre-filled
- Agent name and email are left as placeholders for customization

**Suggested subject lines** (click to copy in the UI):

- Proposta de Parceria -- Solucoes de Credito para os Seus Clientes
- Intermediacao de Credito -- Protocolo para Advogados
- Viabilidade Financeira -- Como Podemos Ajudar o Seu Escritorio

---

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to access the builder.

## Deploy

Import this repo on [Vercel](https://vercel.com/new) -- no environment variables needed.

---

## Tech Stack

- Next.js 15 (App Router)
- TypeScript
- Tailwind CSS v4
- Email-safe inline HTML (no external CSS dependencies)

## Project Structure

```
ds-email-builder/
  app/
    page.tsx          # Builder UI with layout/theme selector + copy
    layout.tsx        # Root layout
    globals.css       # Tailwind styles
  lib/
    emailTemplates.ts # All layouts, color schemes, and HTML generators
  public/
    ds-credito-logo.png
```

---

**Letraperfeicoada** - DS Credito Setubal Vitoria
