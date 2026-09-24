# System Prompt

A standalone, styled article for GitHub Pages. No framework, package installation, analytics, external fonts, or build step. The repository root is the website.

## Preview locally

On macOS:

```bash
open index.html
```

Or serve it over HTTP (binds only to your machine):

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8000. Stop with Ctrl-C.

## Edit

- `index.html`: article, result table, and publication metadata.
- `assets/style.css`: layout and typography, including mobile and print styles.
- `artifacts/`: reviewed input texts and selected result metadata; no raw sessions or credentials.
- `.nojekyll`: serve the files directly without a Jekyll build.

The article is published as a review draft. Author attribution and final wording remain open for revision. Remove the draft markers when the article is finalized.

## Publishing and updates

- Website: https://br0kensmi1e.github.io/system-prompt/
- Repository: https://github.com/Br0kenSmi1e/system-prompt
- GitHub Pages source: branch `main`, folder `/ (root)`.

Edit locally, commit the changes, and push to `main`; GitHub Pages updates the site automatically. Do not upload the original experiment directories or agent profile. No personal homepage, custom domain, or separate build workflow is needed.

## Evidence scope

The post is an experience report, not a system-prompt-versus-skills benchmark. The identity demo has one run per condition in each complete batch. All interrupted batches are disclosed in the article and metadata. Prompt bodies/context files are included, but private full transcripts and experiment workspaces are not.
