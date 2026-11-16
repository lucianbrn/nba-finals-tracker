# The Listening Timeline

Lucian's top 20 artists of all time from his Spotify Extended Streaming History,
ranked by total hours streamed — least streamed (#20) at the top of the page,
most streamed (#1, Drake) at the bottom.

- Data: `top20.json` in the project folder, computed from the Spotify Extended
  Streaming History export of 2026-11-04 (190,010 entries, 2018-01-06 – 2026-11-03),
  ranked by ms_played summed over all music plays.
- Artist portraits: `assets/artists/<slug>.png` — supplied by Lucian; each card
  shows a placeholder frame until its PNG lands.
- Build: `build.py` regenerates `index.html` from `top20.json`.

This site replaced the NBA Finals Tracker on 2026-11-16 at Lucian's order.
The Finals Tracker is fully preserved: `finals.json` stays in this repo,
and every Finals version of `index.html` is in this repo's git history.
