# StablePod

I made this editorial landing page for StableLab to present its StablePod podcast. The show covered DAO governance and DeFi across 29 episodes from 2023 to 2025.

I co-hosted StablePod with Gustav Arentoft and built this page in Astro.

![Screenshot of the StablePod page](docs/screenshot.png)
<!-- screenshot: add docs/screenshot.png -->

## Run it locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open [localhost:4321](http://localhost:4321).

Build for production:

```bash
npm run build
```

The build runs `astro check` followed by `astro build`.

To update the page:

- Replace the cover art at `public/images/podcast-cover.jpg`.
- Edit the page copy and the `platforms` array of listening links in `src/pages/index.astro`.
- Change colors in `src/layouts/Layout.astro`.
- Update fonts in `src/layouts/Layout.astro`. The page loads Crimson Pro and Space Grotesk through Google Fonts.
