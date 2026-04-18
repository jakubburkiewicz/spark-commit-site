# sparkcommit.com

Landing page for the [Spark Commit](https://marketplace.visualstudio.com/items?itemName=JakubBurkiewicz.spark-commit) VS Code extension.

## Stack

- [Astro](https://astro.build) — zero-JS static site generator
- [Tailwind CSS](https://tailwindcss.com) — utility-first styling
- [Cloudflare Pages](https://pages.cloudflare.com) — hosting

## Develop

```sh
npm install
npm run dev          # http://localhost:4321
```

## Build

```sh
npm run build        # output in ./dist/
npm run preview      # preview the built site locally
```

## Deploy

Production deploys happen automatically on every push to `main` via Cloudflare Pages. The custom domain `sparkcommit.com` is configured in the Cloudflare dashboard.

## License

[MIT](./LICENSE)
