# Alex Yu — personal portfolio

[Live website](https://alexyyyander.github.io/) · [GitHub profile](https://github.com/alexyyyander)

A static portfolio for Alex Yu (俞阳阳 / Yangyang Yu), covering AI agent tools,
formal mathematics, multimodal research, and product engineering.

## Structure

- `index.html`: introduction, projects, research, experience, education, and contact.
- `styles.css`: responsive layout, keyboard focus, reduced motion, and print styles.
- `assets/profile-waterfall.jpg`: original portrait.
- `.nojekyll`: serves the files directly through GitHub Pages.

The site uses semantic HTML and system fonts. No JavaScript, dependencies,
API credentials, or build step are required. Content and links work without
client-side rendering or live GitHub API requests.

## Preview

Open `index.html` directly, or run:

```sh
python3 -m http.server 4318 --bind 127.0.0.1
```

Then visit <http://127.0.0.1:4318>.

## Maintain the portfolio

Edit project summaries and links in `index.html`. Keep status labels accurate:
Proofweave has a public reference demo and controlled-alpha research writes;
Teichmüller formalization is partial; the prompt-injection toolkit provides
heuristic screening.

Descriptions were checked against the public repositories on 2026-09-10:

- [Proofweave](https://github.com/alexyyyander/proofweave)
- [Mixxx API Bridge](https://github.com/alexyyyander/mixxx-api-bridge)
- [Prompt Injection Defense](https://github.com/alexyyyander/prompt-injection-defense)
- [Teichmüller’s Unified Program](https://github.com/alexyyyander/teichmuller-tutorial)
- [Merged OpenClaw contribution](https://github.com/openclaw/openclaw/pull/35321)
- [VidEgoThink paper](https://arxiv.org/abs/2410.11623)

Biography, education, thesis, honors, and experience retain the owner-provided
information from the previous homepage. Review ongoing role dates as they change.
Existing anchors `#research`, `#publications`, `#thesis`, `#projects`,
`#experience`, and `#honors` remain available.

## Deployment

GitHub Pages serves the repository root on `main` at
<https://alexyyyander.github.io/>. Merging a change into `main` updates the public
site through the existing Pages build. Keep the deployment on GitHub Pages;
no separate hosting project is needed.
