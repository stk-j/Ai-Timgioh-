# MONTE MAN YES – The Timgioh Clicker

An unofficial fan clicker game for **timgioh.store**. It is a single `index.html` with inline CSS and vanilla JS. There is no build step, no frameworks and no external requests (no Google Fonts, no tracking), so it is GDPR-friendly out of the box.

## Deploy

- **IONOS:** upload `index.html` (and the `assets/` folder, if you add images) into your webspace folder.
- **GitHub Pages:** Settings → Pages → "Deploy from a branch" → pick the branch and `/ (root)`.
- **Local:** just open `index.html` in a browser.

## Customize

Everything you'd want to change is at the top of the second `<script>` block in `index.html`:

- `CONFIG.images` holds the optional pictures (relative paths, e.g. `assets/tim-head.png`). Leave them `''` to use the built-in drawings. See `assets/README.md`.
- `CONFIG` also holds the balancing knobs: price growth (×1.15), offline progress, bonus per chaos layer, and so on.
- `LORE` has all random texts: chat messages, usernames, news-ticker headlines, push notifications, clip titles and spam-bot lines. **This is where your community's own inside jokes and emotes go.**

## What's in the game

- A big **MONTE MAN YES** button with squish, floating numbers, chat bubbles and crit clicks ("ER IST 33?!").
- Ranks from Zuschauer → Chatter → Mod → Yugi-Tuber → Twitch Partner → Viral → Legende. Every rank-up replays the "Bist du Zuschauer?" moment.
- 22 upgrades (price ×1.15 each). They include Booster Packs with Holo pulls, Monte Raids and Deck-Analysen.
- **16 chaos layers** that turn a calm screen into total overload: Twitch chat, stream overlay + webcam, bouncing DVD-Tim (corner bonus!), push notifications, breaking-news ticker, flying kart items (golden = turbo), raining parody cards, rainbow, bass shake, confetti, exploding follower counters, emote storm, clip pop-ups, "Er ist 33?!" ID checks, hype train, and finally total stimulation.
- 3 mini-games: **Mod-Schicht** (ban the spam bots), **Duell!** (parody card duel), **Bananen-Slalom** (kart dodging).
- 44 achievements, offline progress, an ending with credits, and New Game+ seasons.
- Auto-save to `localStorage` every 10 s, a reset button with confirmation, Web Audio sounds with a mute toggle, and a "reduce motion" setting.

All cards, monsters and characters are original parodies. Nothing comes from Konami, Nintendo or Twitch.
