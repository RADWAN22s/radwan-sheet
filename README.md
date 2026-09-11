# Radwan Sheet

Personal planner for Radwan's life, schedule, notes, and future additions.

## What is included

- Personal-life dashboard sections for Today, Goals, Habits, Family & Friends, Health, Travel, Wishlist, and open space.
- A month-style schedule covering 11 September–10 October 2026 in Riyadh time (UTC+3).
- A read-only embedded Google Docs notes preview plus quick notes saved with the planner.
- An owner edit mode for schedule cells, dashboard copy, and quick notes.
- A GitHub save flow that commits updated planner data back to `main`.

## GitHub Pages

The site publishes from the root of the `main` branch using GitHub Pages. The page uses `styles.css` for presentation and `app.js` for the planner data and editing flow.

## In-page editing

Select **Edit on this page** near the bottom of the planner. Highlighted fields become editable, and schedule cells include an **Add event** control. Select **Save to GitHub** when finished, then paste a fine-grained GitHub token with read and write access to this repository. The token is used only in the current browser session and is never written into the page source.

GitHub Pages can take a short time to publish the new commit. The existing GitHub editor and Google Docs links remain available as fallbacks.
