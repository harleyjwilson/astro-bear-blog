# Astro Bear Blog Theme

Create a blog with Astro based on the [Bear Blog](https://bearblog.dev) styling.

Features:

- ✅ Minimal styling (make it your own!)
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Markdown support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   ├── pages/
│   ├── styles/
|   └── bear-blog-theme.json
├── astro.config.mjs
├── README.md
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

the components that make up the pages are in the  `src/components/` directory.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`.

The custom theme for the markdown rending of code blocks via Shiki is stored in the `bear-blog-theme.json` file. 

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Acknowledgement

This theme is based off of the amazing [Bear Blog](https://github.com/HermanMartinus/bearblog/).