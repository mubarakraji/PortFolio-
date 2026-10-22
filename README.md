# Mubarak Portfolio

A data-driven portfolio built with Next.js 16, React, TypeScript, and Tailwind CSS.

## Project structure

- `src/app` contains the App Router pages and global styles.
- `src/components` contains reusable layout, section, and project components.
- `src/data` contains portfolio content so it can be updated without changing UI code.
- `src/types` contains shared TypeScript models.
- `public/images` and `public/documents` contain static portfolio assets.

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

## Content and assets

Update the project content in `src/data/projects.ts`, then add matching project images at:

```text
public/images/projects/paybankx.webp
public/images/projects/rocky-earth.webp
```

Project routes are generated from the project slugs:

```text
/projects/paybankx
/projects/rocky-earth
```

The GitHub username is configured in `.env.local`. Add
`NEXT_PUBLIC_SITE_URL` when the production domain is available.

The profile image, Open Graph image, and resume can be added under the paths in
the project structure when those final assets are available.

## Checks

```bash
npm run lint
npm run build
```
