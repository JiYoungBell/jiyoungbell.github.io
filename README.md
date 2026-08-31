# jiyoung.win

Static personal portfolio built with Astro. The design treats the page as a technical field note: a restrained document grid, revision markings, and shared flow diagrams for infrastructure and live audio.

## Local development

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

The generated site is written to `dist/`.

## GitHub Pages

The workflow in `.github/workflows/deploy.yml` builds and publishes the site when `main` is pushed. In the repository settings, set **Pages → Source** to **GitHub Actions**. The `public/CNAME` file configures the custom domain `jiyoung.win`.
