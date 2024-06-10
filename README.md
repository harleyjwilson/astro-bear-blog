# Astro Bear Blog

Create a blog with Astro based on the [Bear Blog](https://bearblog.dev) design.

Features:

- ✅ Make use of Bear Blog's amazing design
- ✅ Small webpage sizes (~290B for the homepage)
- ✅ Addd blog posts by adding the Markdown files in the `src/content/blog` directory
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Filter your blog posts by using tags
- ✅ Use DuckDuckGo to search your blog
- ✅ Automatically generated RSS feed and sitemap

## 🚀 Project Structure

Inside of your Astro project, you'll see the following key folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   ├── pages/
│   ├── styles/
|   └── consts.js
├── astro.config.mjs
├── LICENSE
├── package.json
└── README.md
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

The components that make up the pages are in the `src/components/` directory.

The `src/content/blog` directory contains a collection of Markdown documents that are your blog posts.

Any static assets, like images, can be placed in the `public/` directory.

Variables to configure your site like your `SITE_TITE`, `SITE_DESCRIPTION`, `SITE_URL`, and `SEARCH_URL` are in the `src/consts.js` file.

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

The design is a migration of the amazing [Bear Blog](https://github.com/HermanMartinus/bearblog/), using the Astro blog template to start it off.