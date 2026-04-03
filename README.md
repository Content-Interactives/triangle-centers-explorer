# Triangle Centers Explorer

Next.js 14 **App Router** app (`src/app/`): drag triangle vertices and visualize **centroid**, **circumcenter**, **incenter**, and **orthocenter** with optional construction lines (medians, perpendicular bisectors, angle bisectors, altitudes).

## Stack

- Next.js 14, React 18
- TypeScript 5
- Tailwind CSS 3
- Lucide React

## Setup

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Scripts

| Command | Description |
|--------|-------------|
| `npm run dev` | Next.js dev server |
| `npm run build` | Production build |
| `npm run start` | Run production server |
| `npm run lint` | `next lint` |
| `npm run build:static` | Repo script: `next build && next export` — prefer `npm run build` when `next.config.js` uses `output: 'export'` |

## Configuration

`next.config.js`: static export (`output: 'export'`), production `basePath` / `assetPrefix` `/triangle-centers-explorer` for GitHub Pages.

## Implementation notes

- Geometry updates client-side from draggable vertex positions.
- Toggle layers control which centers and auxiliary segments render.

## License

MIT (see repository if a `LICENSE` file is present).
