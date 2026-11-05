# Chess Puzzles — Mate in N

Free single-file HTML5 chess puzzle game: 100 hand-checked checkmate puzzles
(Mate in 1 / 2 / 3), organized by tactical theme (Queen & Rook, Two Rooks,
Castling, Queen & Bishop, promotions and more).

Play: https://shuangyueliao.github.io/chess-puzzles/

## How to play

- White always moves first and always delivers checkmate.
- Tap/click a white piece, then tap its destination. Legal landing squares are
  marked. Wrong moves cost a mistake — the position does not change.
- After your correct move, Black plays its stored best defense; keep forcing
  until checkmate.
- Levels unlock progressively: solve 15 puzzles in a tier to open the next.
- Best times per puzzle, solve streak, and total progress are saved in
  localStorage.

## Features

- 100 curated mate-in-N puzzles (40 / 35 / 25 across three tiers)
- Complete chess rules engine: full move legality including castling, en
  passant, promotion, check/checkmate/stalemate detection
- Move animation, check highlight, last-move markers, legal-move hints
- Procedural piece rendering (canvas) and WebAudio sound effects — zero
  external assets, works offline once loaded
- Touch + mouse input, responsive canvas
- Progress saved locally; mute toggle

## Tech

Vanilla JavaScript, single `index.html` (~65 KB), no frameworks, no tracking,
no external links. Portal SDKs (CrazyGames / GameDistribution) load only on
their own domains.

## License

MIT
