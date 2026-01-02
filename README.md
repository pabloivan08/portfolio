![basics](./src/assets/demo/readme-demo.png)


https://pabloivan.io

### Dependencies used in this project:
- [TailwindCSS](https://tailwindcss.com/)
- [GSAP](https://gsap.com/)
- [Remix Icon](https://remixicon.com/)



Within the Portafolio you'll see the following folders:

```text

├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   └── Bars.astro
        └── Button.astro
        └── CallToAction.astro
        └── Footer.astro
        └── Header.astro
        └── Hero.astro
        └── MarddownPost.astro
        └── Reviews.astro
        └── Service.astro
        └── Work.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
        └── posts/
        └── blog.astro
        └── index.astro
└── styles/
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
