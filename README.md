# Personal link page

Single-page profile and link hub — junior full-stack developer, Naples (Italy).

Plain HTML and CSS, no build step, no dependencies. Published with GitHub Pages.

- `index.html` — the whole page (styles included)
- `.nojekyll` — tells GitHub Pages to serve the files as they are

## Editing

Open `index.html` and edit the text directly. Places still to fill in are marked
with `TODO` comments:

| What | Where |
|---|---|
| GitHub profile URL | contact section |
| LinkedIn profile URL | contact section |
| Mini Shop live URL | work section |
| Job Tracker live URL | work section |
| Job Harvester repo URL | work section |

Each of those is currently a `<div class="row pending">`. Once the real link
exists, turn it into `<a class="row" href="...">` and remove `pending`.

## Publishing a change

```
git add -A
git commit -m "update"
git push
```

The live page updates within a minute.
