# medseas

A personal "second brain" dashboard — quick tasks and notes, as a backstop for day-to-day work.

## Status

MVP: static HTML/CSS/JS page with local-storage persistence (data stays in your browser only, nothing synced anywhere yet). No backend or database — that's a deliberate next step, not an oversight.

## Running it

Open `index.html` in a browser, or serve the folder with any static file server.

## Hosting

Deploys automatically to GitHub Pages on every push to `main`, via `.github/workflows/deploy-pages.yml`.

**One-time setup required:** in this repo's GitHub settings, go to **Settings → Pages → Build and deployment → Source**, and select **GitHub Actions**. After that, every push to `main` publishes automatically.

## Roadmap

- Real persistence (a database) so notes/tasks aren't stuck to one browser
- Possibly rebuilt/extended via Lovable once the shape of the thing is clearer

## Expert Desk

A second page lives at `/expert-desk/` — a placeholder dashboard with tab navigation (Dashboard / Experts / Assignments / Notes), no content wired up yet. This was going to be its own repo, but repo creation isn't available through this GitHub connection, so it lives here as a subfolder instead. Move it out to its own repo later if it grows into a separate project.

## Development

This repo is currently **public** on GitHub — fix that in Settings → General → Danger Zone → Change visibility, if it should be private.
