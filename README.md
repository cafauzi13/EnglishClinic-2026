# EC Database 2026

Link hub for **CSS English Clinic 2026** (KESMA CSSMORA ITS): class materials, class exercises, simulations, and report cards in one place.

Single static page, no build step. Everything lives in `index.html`.

## Change a link

1. Open `index.html` and find the `DATA` block near the top of the `<script>`.
2. Edit the `url` of the item you want. Use `url: null` for an item that is not ready yet (it shows as "Coming soon").
3. Commit the change. The site updates automatically after about a minute.

Item types:
- `type: "branch"` opens another level (it has `children`).
- `type: "leaf"` opens its `url` in a new tab.

## Publish (GitHub Pages)

Settings, then Pages, then Source: *Deploy from a branch*, then `main` / `(root)`.

## Privacy

The page is public. Do not put links to folders or files that contain personal data (for example report cards) unless their sharing is restricted to the intended people.
