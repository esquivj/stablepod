# Stablepod Landing Page

An editorial-style podcast landing page built with Astro, featuring a magazine aesthetic with bold typography and refined design.

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Add your podcast cover:**
   - Replace the placeholder at `/public/images/podcast-cover.jpg` with your actual podcast cover art
   - Recommended size: 1400x1400px or larger
   - Format: JPG or PNG

3. **Update content:**
   - Edit `/src/pages/index.astro` to update:
     - Podcast title, tagline, and description
     - Platform URLs (YouTube, Spotify, Apple Podcasts)

4. **Run development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:4321](http://localhost:4321) in your browser.

5. **Build for production:**
   ```bash
   npm run build
   ```

## Design Features

- **Editorial aesthetic:** Magazine-inspired layout with sophisticated typography
- **Typography:** Crimson Pro (serif) for headlines, DM Sans (sans-serif) for body text
- **Dark theme:** Deep navy background with warm coral accents
- **Animations:** Staggered fade-in on page load, smooth hover transitions
- **Responsive:** Mobile-first design that adapts to all screen sizes
- **SEO optimized:** Meta tags, Open Graph, and structured data included

## Project Structure

```
/
├── public/
│   └── images/
│       └── podcast-cover.jpg    # Replace with your cover art
├── src/
│   ├── layouts/
│   │   └── Layout.astro         # Base layout with SEO
│   └── pages/
│       └── index.astro          # Landing page
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Deployment

This site is ready to deploy to Vercel, Netlify, or any static hosting platform.

### Vercel
```bash
npm install -g vercel
vercel
```

## Customization

- **Colors:** Edit CSS variables in `/src/layouts/Layout.astro`
- **Fonts:** Update Google Fonts link in layout head
- **Platform links:** Add or remove platforms in `/src/pages/index.astro`

## License

Created for StableLab.
