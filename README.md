# Bout Board

A bracket maker for robot sumo competitions that works for any tournament. It's a single HTML file: no install, no server, no account.

**Open it:** https://dan007b.github.io/bracket-maker/

## Features

- **Five bracket styles**
  - Single elimination, with an optional 3rd-place match and the final on the right or in the center
  - Double elimination, with a grand final and an optional bracket reset
  - Round robin, with standings
  - Swiss, with a set number of rounds and pairing by record
  - Groups + playoffs: round-robin pools, then single elimination
- **2–64 teams.** Byes go to the top seeds automatically. Seed by list order or shuffle.
- **Click a team to record the win.** Best-of-1, 3 or 5 matches, where each click counts one round. Click the winner again to undo. Anything later in the bracket that depended on it asks before clearing.
- **Next up and on deck** are highlighted so you always know which match is next.
- **Highlight a match** to see where its teams came from and where its winner and loser go.
- **Match view** shows a single match full screen for a projector. It moves on to the next match automatically when one finishes.
- **Present bracket** shows the whole bracket full screen. Zoom and Fit make it readable.
- **Save image** saves a PNG of the bracket and podium once the final is played.
- **Export / Import** moves a tournament between devices as a JSON file. Progress also saves in the browser automatically.

## Run it locally

Download `index.html` and open it in any modern browser. It works offline, except for the web fonts.

## Notes

Results are saved in the browser you use, so run an event from one device and use **Export** to back it up.

## License

[MIT](LICENSE)
