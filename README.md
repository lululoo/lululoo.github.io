# Matt's Personal Site

## 🚀 Project Structure

This is an [Astro project](https://astro.build/). You'll see the following folders and files:

```text
/
├── public/             static assets
├── src/
│   ├── assets/         static assets
│   ├── components/     Astro components
│   ├── layouts/        Astro layouts
│   └── pages/          Astro pages
│   └── styles/         CSS
└── package.json
```

## Getting Started

Run:
```
npm install
npm run build
npm run dev
```

## Deployments

Files are statically generated and 'deployed' into the `docs` directory, which get served as GitHub pages.

After making any changes, run: `npm run deploy` and commit the changes in the `docs` directory.

A GitHub action on the repo will kick off and deploy the latest content.

## 🧞 Dev Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run clean`           | Remove all files in  `./dist/`                   |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run deploy`          | Deploy your build to `docs`                      |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
