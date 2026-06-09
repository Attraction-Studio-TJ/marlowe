# Marlowe

Astro prototype for the Marlowe interactive image mosaic.

## Current Route

- `/` - two-frame 4x5 image mosaic with once-only tile reveals and a menu scatter interaction.

## Project Structure

```text
/
├── public/
│   ├── 1/                 # first mosaic image set
│   └── 2/                 # second mosaic image set
├── src/
│   └── pages/
│       └── index.astro    # current Marlowe page
└── package.json
```

## Commands

| Command | Action |
| :-- | :-- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site to `dist/` |
| `npm run preview` | Preview the production build |
