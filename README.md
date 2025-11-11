# Search Builder

Quick Boolean query builder for sourcing roles. The page is fully client-side, so you can run it locally or host it anywhere (GitHub Pages, Netlify, etc.).

## Features
- Live Boolean query preview with copy-to-clipboard
- Preset job board filters (LinkedIn, Indeed, Dice, BuiltIn, Google Jobs, Robert Half)
- Optional company requirement toggle and operator mode (explicit AND, implicit space, OR)
- Exclusion presets (No contracts, freelancers, agencies, juniors, entry level, 1099) plus custom excludes
- Saved queries stored in localStorage (name, save, load, delete)
- Bookmark launcher with favicons for quick access to favorite job sites
- Time range parameter for Google searches (24h, 3 days, week)
- Works with Google, Bing, and DuckDuckGo search URLs

## Running Locally
Open the HTML file in any browser:

```
open searchbuilder.html   # macOS
start searchbuilder.html  # Windows
```

or drop it into a simple static server:

```
npx serve
```

## Hosting
- **GitHub Pages**: push to main, enable Pages on the repo. If you rename the file to `index.html`, it serves at the root URL.
- **Netlify / Vercel / Cloudflare Pages**: drag-and-drop or point the service at this repo—no build step necessary.

## Saving & Sharing Queries
Saved queries are stored in the browser’s localStorage. They don’t sync between devices; export your query by hitting “Copy Boolean query” and storing it in a doc or repo if you need versioned history.

## Contributions
Fork it, tweak it, build more presets. PRs welcome.

