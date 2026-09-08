# blinky-legal

The privacy policy and terms of use for [Blinky](https://play.google.com/store/apps/details?id=com.jbli19.blinky),
a notification light for phones that do not have one.

This repository is public because Google Play requires a privacy policy URL that
loads without signing in. Blinky's source lives in a private repository.

## Do not edit these files here

`index.html`, `privacy.html` and `terms.html` are generated. The text they hold
is the same text the app shows in Settings, and it comes from a single source in
the Blinky repository:

```
src/app/core/constants/legal.ts
```

To change a document, edit that file, then run:

```bash
npm run legal
```

That writes `PRIVACY.md` and `TERMS.md` at the root of the Blinky repository and
the three pages under `store/legal/`. Copy those three pages here and push.
Editing them here instead makes the published policy disagree with the one in
the app, which is the thing this arrangement exists to prevent.

## Published at

<https://billyli19.github.io/blinky-legal/>

Served by GitHub Pages from the `main` branch, root folder.
