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

- `index.html`: the first-person story about guiding research judgment rather than prescribing a procedure.
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

The post is rooted in the original conversation and its September 23–24 follow-up. Its narrative distinguishes the mechanical-workflow problem, resolved for this setup by the minimal prompt, from premature commitment and stopping, which remain unresolved. The follow-up supplies the repeated DP framing, uncertainty-driven investigation proposal, and untested main-agent/implementation-worker separation. These are reported observations and proposed interventions, not a system-prompt-versus-skills benchmark. The historical research prompt is exported in `artifacts/research-system-prompt.txt`. The inconclusive identity demo is no longer part of the article. Its previously published inputs and metadata, including interrupted batches, remain in `artifacts/` for historical reference. Prompt bodies/context files are included, but private full transcripts and experiment workspaces are not.
