# Blog

## 🧞 Comandos

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Estructura de carpetas

```
├── astro.config.mjs
├── package.json
├── package-lock.json
├── public
│   └── favicon.svg
├── README.md
├── src
│   ├── components
│   │   ├── BlogPost.astro
│   │   ├── Header.astro
│   │   ├── HeaderButton.astro
│   │   ├── Navigation.astro
│   │   └── TagButton.astro
│   ├── env.d.ts
│   ├── layouts
│   │   ├── MainLayout.astro
│   │   └── MarkdownPostLayout.astro
│   ├── pages
│   │   ├── about.astro
│   │   ├── blog.astro
│   │   ├── index.astro
│   │   ├── posts
│   │   │   └── 001-caracteristicas-principales-de-react-js-en-desarrollo-web.md
│   │   └── tags
│   │   ├── index.astro
│   │   └── [tag].astro
│   └── scripts
├── tailwind.config.mjs
└── tsconfig.json
```
