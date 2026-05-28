# Management Overview

Single-page dark-mode overview for a collection of interactive management dashboards.

## Contents

- `index.html` - Deploy entry point for GitHub Pages and static hosts.
- `management_overview.html` - Main overview page that embeds all dashboards.
- `sop_interactive_explainer.html` - S&OP cycle interactive explainer.
- `toc_wip_pipeline_simulator.html` - Theory of Constraints pipeline simulator.
- `wip_limits_interactive_explainer (1).html` - WIP limits Kanban simulator.
- `risk_management_master_course.html` - Risk Management progressive course dashboard.
- `brd_management_ecosystem.svg` - BRD ecosystem management diagram.

## Open Locally

Open `index.html` directly in a browser.

For a local server:

```bash
python -m http.server 8765
```

Then visit:

```text
http://127.0.0.1:8765/management_overview.html
```

Or open:

```text
http://127.0.0.1:8765/
```

## Deploy

This repository is ready for GitHub Pages, Netlify, Vercel, or any static host.

For GitHub Pages, enable:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

Expected GitHub Pages URL:

```text
https://designedby-radol.github.io/management-overview/
```

## Notes

All templates are static HTML/SVG assets and use a dark visual theme. No build step or package installation is required.
