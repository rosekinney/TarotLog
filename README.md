# ✦ Tarot Log ✦

A minimalist tarot journal: snap a photo of your cards, add your own notes, and get an automatic card scan with a short synopsis (kept separate from your notes).

## Features
- Photo + notes log, private to each signed-in user
- Card scan that maps any deck's themed names (e.g. "Six of Pumpkins") to the standard Rider-Waite card
- Cards shown as recolored Rider-Waite-Smith art (Pamela Colman Smith, 1909, public domain) with an iridescent finish; cards without matching art are skipped
- Insights tab: most-pulled cards, suit pie chart, and a ★ on your most-pulled card, all using conventional card names (unidentified cards are left out)

## Running it
`index.html` is a single self-contained page built to run as a Claude artifact. Sign-in, private storage and the card scan come from the Claude runtime, so they won't work when the file is opened directly or hosted on GitHub Pages. Open the shared artifact link inside Claude instead.

## Notes
- Card art: 78 public-domain scans, recolored and embedded as JPEGs (~2 MB).
