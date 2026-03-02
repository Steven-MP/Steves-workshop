# Steve's Workshop Blog

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)

Welcome to the official blog for **Steve's Workshop**. This site is built with [Astro](https://astro.build) and uses [TinaCMS](https://tina.io) for editing content.

## About

The site was originally created from a blog template by [Cassidy Williams](https://github.com/cassidoo). All front‑end code is powered by Astro and content is managed through TinaCMS.

## Running Locally

All commands are run from the root of the project, from a terminal:

| Command                          | Action                                                        |
| :------------------------------- | :------------------------------------------------------------ |
| `npm install`                    | Installs dependencies                                         |
| `npm run dev`                    | Starts local dev server at `localhost:4321`                   |
| `npx tinacms dev -c 'astro dev'` | Manually run local server if the regular command doesn't work |
| `npm run build`                  | Build your production site to `./dist/`                       |
| `npm run preview`                | Preview your build locally, before deploying                  |

Visit `http://localhost:4321/admin/index.html` to access the TinaCMS interface. A `.env.development` file with the following variables is required for local editing:

```
TINACLIENTID=<from tina.io>
TINATOKEN=<from tina.io>
TINASEARCH=<from tina.io>
```

If you encounter a remote GraphQL schema error, update TinaCMS according to the [FAQ](https://tina.io/docs/introduction/faq#how-do-i-resolve-the-local-graphql-schema-doesnt-match-the-remote-graphql-schema-errors).

> **Note:** Editing `public/rss-styles.xsl` does _not_ hot reload; refresh the page to see changes.

## Credits

This project uses the [blahg](https://github.com/cassidoo/blahg) template by Cassidy Williams. Thanks to Cassidoo for the excellent starter — check out the original repository for details.

---
