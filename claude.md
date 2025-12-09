# viktorzavadil.cz

Osobní web a blog Viktora Zavadila.

## Tech Stack
- **Astro 5** (SSG)
- **Tailwind CSS 4** + **DaisyUI 5** (theme: night)
- **MDX** pro blog
- **TypeScript**

## Struktura
```
src/
├── components/    # Header, Footer
├── content/blog/  # MDX články (frontmatter: title, description, pubDate, tags, draft)
├── layouts/       # BaseLayout.astro
├── pages/         # index, blog/index, blog/[...slug]
└── styles/        # global.css (Tailwind + DaisyUI)
```

## Příkazy
- `npm run dev` - dev server
- `npm run build` - build
- `npm run preview` - preview

## Konvence
- Blog soubory: slug bez data (např. `home-assistant-server.mdx`)
- Komponenty: Astro (.astro)
- Styling: Tailwind utility classes + DaisyUI komponenty
- Tón textů: přátelský, ne prodejní