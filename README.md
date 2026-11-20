# Showcase

Public deployment of personal apps and learning projects. Source code stays private; only the compiled output is published here to GitHub Pages.

**Live:** https://hugoagfarizky.github.io/showcase/

## What's inside

| App | Description | Link |
|---|---|---|
| Monorepo | Interactive GitHub monorepo planner | [Open](https://hugoagfarizky.github.io/showcase/monorepo/) |
| RepoForge | Workbench to discover repo ideas and scaffold them | [Open](https://hugoagfarizky.github.io/showcase/repoforge/) |
| GitCraft | Repository architect & 2-week Full-Stack/SaaS blueprint | [Open](https://hugoagfarizky.github.io/showcase/gitcraft/) |
| First Dev Projects | 20 vibecoding learning projects | [Open](https://hugoagfarizky.github.io/showcase/first-dev-projects/) |

## How it works

1. Each source repo is built with its own toolchain (Vite, Next.js static export, Flutter web).
2. The compiled output is collected into this repo under a matching subfolder.
3. GitHub Pages serves the whole folder tree; each subfolder becomes its own URL.
4. Pushing to a source repo triggers a rebuild and redeploy.

## Privacy

No backend and no database. All apps run entirely in the visitor's browser; user data stays in `localStorage` / `IndexedDB` on the visitor's own device.

## License

[MIT](LICENSE)
