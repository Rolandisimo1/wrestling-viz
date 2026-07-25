# NCAA Wrestling — Interactive Visualizations

A century of NCAA Division I wrestling (1928–2026) and the high-school pipeline that feeds it,
visualized interactively. Program trajectories, recruit development, coaching histories, and
individual careers.

## Live site

Once GitHub Pages is enabled (Settings → Pages → deploy from `main` branch, root), the site is at:

    https://<your-username>.github.io/wrestling-viz/

## Visualizations

- **index.html** — landing page linking everything
- **recruit_explorer.html** — wrestlers by high-school (Fargo freestyle) finish vs. NCAA points; filter by school and year
- **ncaa_program_timeline.html** — compare 2–4 programs: recruiting rank vs. NCAA team points, with coaching changes
- **ncaa_college_explorer.html** — program-by-program All-American placement history
- **coaching_grid.html** — who coached where and when, in school colors
- **\*_mobile.html** — touch-optimized versions of the larger explorers

Every file is a self-contained single HTML document — no build step, no external
dependencies. Open any of them directly in a browser, or email/share the file.

## Data sources

NCAA championship brackets (re-parsed from source tournament PDFs, 1928–2026) and
Fargo/USMC Junior & 16U national placements (1971–2025).

## Enabling GitHub Pages

1. Push this repo to GitHub (public).
2. Repo → **Settings** → **Pages**.
3. Source: **Deploy from a branch**, Branch: **main** / **/(root)**, Save.
4. Wait ~1 minute; your link appears at the top of the Pages settings.
