# sugiro.ai

Lula Rocha's Personal portfolio site showcasing design work and AI-related tools.

**Live site:** https://sugiro.ai

## Tech Stack

- [Astro](https://astro.build) — static site framework
- React — component integration
- Tailwind CSS — styling via Vite plugin
- DM Sans — typography (Google Fonts)

## Project Structure

```
/
├── public/          # Static assets
├── src/
│   ├── components/  # Header, Footer, Layout
│   ├── pages/       # Route pages (.astro)
│   └── styles/      # Global CSS
└── astro.config.mjs
```

## Pages

| Route | Description |
| :---- | :---------- |
| `/` | Home — featured project cards |
| `/about-me` | Personal bio and resume |
| `/about-sugiro` | About the brand |
| `/generative-design` | Generative design project gallery |
| `/more-projects` | Full graphic and web design portfolio |

## Commands

| Command | Action |
| :------ | :----- |
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run build` | Build to `./dist/` |
| `npm run preview` | Preview production build locally |
