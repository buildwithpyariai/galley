# Galley Website

The official website for Galley — your coffee co-pilot.

## Develop

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) to preview.

## Build

```bash
npm run build
```

Output is in the `dist/` folder.

## Configuration

- **WhatsApp:** Set `WHATSAPP_NUMBER` in `src/pages/index.astro` (line 6) — e.g. `919876543210` for India (country code + number, no + or spaces).
- **Contact form:** The form currently has `action="#"`. Connect it to [Formspree](https://formspree.io), [Netlify Forms](https://docs.netlify.com/forms/setup/), or another form service for handling submissions.
- **Social links:** Update the Facebook and Instagram `href` values in the Social section.

## Deploy (Netlify / Vercel)

1. Push this project to GitHub
2. Connect the repo to [Netlify](https://netlify.com) or [Vercel](https://vercel.com)
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Add your custom domain `galley.in` in the hosting dashboard
6. Update DNS at your domain registrar to point to the host

## Project Structure

```
├── public/images/     # Logo and website images
├── src/
│   ├── layouts/       # Layout.astro
│   └── pages/         # index.astro
├── astro.config.mjs
└── package.json
```
