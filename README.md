# awesome-bluprints
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome list of [bluprints](https://github.com/reuters-graphics/bluprint) that do awesome things created by and for the Reuters Graphics team.

## Bluprints

- [Graphics rig](#graphics-rig)
- [Graphics rig + Google docs](#graphics-rig--google-docs)
- [GitHub Actions Scraper](#gitHub-actions-scraper)
- [Chart module](#chart-module)
- [Node library](#node-library)
- [Node CLI](#node-cli)

---

### [Graphics rig](https://github.com/reuters-graphics/bluprint_graphics-rig)

**What it does:** Single page graphic builder for interactive graphics.

```
$ bluprint add reuters-graphics/bluprint_graphics-rig
``` 

### [Graphics rig + Google docs](https://github.com/reuters-graphics/bluprint-google-doc-template)

**What it does:** Graphics rig stuff PLUS specifically designed to wire into a google doc, and builds a page by looping through blocks in the document. There are blocks for text, graphic, photo, and ai2html with OPTIONAL extra data on graphics and photos (captions and chart headlines et cetera will only show up if those keys exist).

```
$ bluprint add reuters-graphics/bluprint-google-doc-template
```

### [GitHub Actions Scraper](https://github.com/reuters-graphics/bluprint_github-action-scraper)

**What it does:** Quickstart for building Node-based scrapers that run on a timer via [GitHub Actions](https://github.com/features/actions).

**In the wild:**
 - [COVID-19 hospitalizations in Europe](https://github.com/reuters-graphics/action_covid-europe-hospitalisations)
 - [Google mobility tracker](https://github.com/reuters-graphics/action_google-mobility-tracker)

```
$ bluprint add reuters-graphics/bluprint_github-action-scraper
```

### [Chart module](https://github.com/reuters-graphics/bluprint_chart-module-svelte)

**What it does:** Builds reusable, npm-installable chart modules.

```
$ bluprint add reuters-graphics/bluprint_chart-module-svelte
```

### [Node library](https://github.com/reuters-graphics/bluprint_node-library)

**What it does:** For building simple Node or JavaScript utility libraries, with built-in testing and bundling via [Rollup](https://rollupjs.org/guide/en/).

```
$ bluprint add reuters-graphics/bluprint_node-library
```



### [Node CLI](https://github.com/reuters-graphics/bluprint_node-cli)

**What it does:** For building Node command line interfaces, with arg parsing from [sade](https://www.npmjs.com/package/sade), built-in mocha testing and bundling via [Rollup](https://rollupjs.org/guide/en/).

```
$ bluprint add reuters-graphics/bluprint_node-cli
```
