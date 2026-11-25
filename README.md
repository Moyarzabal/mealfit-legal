# MealFit public pages

Static copies of the in-app `/privacy` and `/support` pages, published with GitHub Pages at
https://moyarzabal.github.io/mealfit-legal/ (public repository `Moyarzabal/mealfit-legal`).
App Store Connect links to `privacy/` and `support/` there.

When `src/routes/privacy.tsx`, `src/routes/support.tsx` or `src/lib/legal.ts` change, update the
HTML here in the same commit, then publish:

```sh
npm run site:publish
```
