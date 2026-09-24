# Joe Sournair — React Portfolio

Codegrid Monthly Website Template (June 2023). Create React App + framer-motion page transitions + react-router.

Live: https://kiarashsajadian.github.io/joe-sournair-portfolio/

## Develop

```bash
npm install
npm start
```

## Deploy

```bash
npm run deploy
```

Builds the site and pushes `build/` to the `gh-pages` branch, which GitHub Pages serves. Pushing to `main` only saves the source; run `npm run deploy` to update the live site.

- `homepage` in `package.json` sets the `/joe-sournair-portfolio/` base path; the router reads it through `basename`.
- The build copies `index.html` to `404.html` so refreshing `/project` still loads the app.
- Neue Montreal (400/500) is bundled from `src/Fonts`. It is a Pangram Pangram font; check its license before using this commercially.
