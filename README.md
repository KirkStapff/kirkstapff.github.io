# Kirk Stapff — Systems notebook

Personal portfolio and notebook at https://kirkstapff.github.io.

## Edit and preview

The site is static HTML with inline CSS and JavaScript. `index.html` is the homepage, including a three-level, top-down Workspace tree with selectable example branches. `workspace.html` is the Workspace project post; `notes/` contains research posts and `assets/` contains figures and screenshots. Open the pages in a browser to preview. There are no dependencies or build steps.

## Deploy

GitHub Pages should be configured under **Settings → Pages → Deploy from a branch → main → / (root)**. Push changes to `main` to publish automatically. `.nojekyll` tells Pages to serve the static files directly.

The homepage links to the recurrent-depth Z1T research post at
`notes/recurrent-depth-z1t.html`. The Workspace notebook entry links to `workspace.html`; other notebook entries remain labeled as ideas.
The post's main figure and PDF are copied from the accompanying
`KirkStapff/rz1t` research repository; update them there first if the
results change. The compiled report is served at `assets/rz1t/rz1t.pdf`.

The post uses seven supplied app screenshots in `assets/workspace/`, following Harbor, a small task app, through prompting, branching, tools, and file previews. Each links to the full-size image. Keep captions and alt text in `workspace.html` up to date when replacing them. The earlier portfolio-project captures remain in `assets/workspace-*.png` but are no longer displayed.
