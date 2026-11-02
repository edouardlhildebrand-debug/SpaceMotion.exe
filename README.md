# SpaceMotion.EXE

A browser-based beat-synced video editor.

## Local development

Requires Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

Vite outputs the deployable site into `dist/`. Cloudflare Pages should use:
- Build command: `npm run build`
- Build output directory: `dist`
- Production branch: `main`
