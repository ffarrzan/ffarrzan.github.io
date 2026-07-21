# Farzan Karimi-Malekabadi — personal site

A single-file, static personal website. No build step, no dependencies.

## Publish on GitHub Pages (5 minutes)

1. Create a new repo. For a personal site at `https://<username>.github.io`,
   name the repo **`<username>.github.io`**. (Any repo name also works — the URL
   just becomes `https://<username>.github.io/<repo>`.)
2. Add **`index.html`** (and your `profile.jpg`) to the repo and commit.
3. Repo → **Settings → Pages** → *Build and deployment* → Source: **Deploy from a branch**,
   Branch: **main** / **/(root)** → **Save**.
4. Wait ~1 minute, then open your Pages URL.

## Before you publish — 3 quick edits in `index.html`

1. **Photo** — drop a file named `profile.jpg` next to `index.html`.
   If it's missing, a clean "FKM" placeholder shows automatically, so nothing breaks.
2. **Links** — search the file for `REPLACE-ME` and paste your real
   **Google Scholar** and **LinkedIn** URLs (two spots each in the header + footer).
3. **Code links** — the six featured papers each have a `Code` button set to `href="#"`
   (search for `<!-- code -->`). Paste your GitHub repo URLs there. Any you leave as `#`
   render as a dashed "Code ·edit" hint — remove that `<a>` line for papers with no repo.

## Customize

- Colors and fonts live in the `:root { … }` block at the top of the `<style>`.
- The faint curve behind your name is an item-response / logistic curve (an SVG in the
  header) — a nod to your psychometrics work. Delete the `<svg class="curve">` block to remove it.
