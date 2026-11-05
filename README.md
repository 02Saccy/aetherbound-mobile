# AETHERBOUND — Mobile Browser Prototype v0.1

A playable, dependency-free HTML/CSS/JavaScript prototype. No account, payment, tracking, backend or external assets required.

## Play

1. Extract the ZIP.
2. Open `index.html` in a desktop browser, or host the folder as a static website to play on a phone.
3. For mobile, upload the entire folder to a static hosting service such as Netlify Drop or GitHub Pages and open the resulting HTTPS URL in Safari/Chrome.

Opening a local HTML file directly on iOS can be unreliable; static HTTPS hosting is recommended. This ZIP is **not** itself a live website.

## Features

- 20 original fantasy champion cards, six rarity tiers.
- Five-card booster packs costing 100 coins; four standard slots and one guaranteed Rare-or-better slot.
- 500 starting coins; 150 bonus coins claimable every 60 seconds.
- Card reveal animation, collection grid, rarity filters, duplicates and local save.
- No real-money purchases.

## Known limits

- Character art is represented by stylized emoji/sigil placeholders; bespoke illustrated anime artwork is not yet included.
- No online multiplayer, trading, accounts or cloud saves in v0.1.
- Coin claiming is a prototype mechanic, not server-validated; browser storage can be cleared.
- Rarity odds are per rarity category and do not imply equal odds for individual cards.

## Next milestone

Add two-player private rooms, backend-authenticated inventory, shared pack reveal sessions and trading with server-side transaction validation. Avoid trusting localStorage for multiplayer inventory.
