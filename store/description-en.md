# Chess Puzzles — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

100 chess checkmate puzzles. Find the forced mate in 1, 2 or 3 moves — clean
positions, real chess rules, hand-checked solutions. How fast can you mate?

(Character count: 148)

## Details

- Genre: Puzzle / Board / Chess
- Controls: Mouse / Touch (tap a piece, tap its destination). Keyboard: Esc returns to menu.
- Features: 100 mate-in-N puzzles in three tiers (Mate in 1 / 2 / 3), tactical
  themes (Queen & Rook, Two Rooks, Castling, Queen & Bishop, promotions,
  deflection and more), full chess rules engine (castling, en passant,
  promotion, check/checkmate/stalemate), move animation, check highlight,
  legal-move hints, best times, solve streak, progressive unlock.
- Tech: Vanilla JavaScript, single-file HTML5 (~64 KB), Canvas rendering with
  procedurally drawn pieces, WebAudio synthesized sounds. No frameworks, no
  tracking, no external assets — works offline once loaded.
- Persistence: best times / solved set / streak in localStorage.

## Tags

chess, puzzle, checkmate, mate-in-2, board, brain, tactics, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to viewport, touch friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover art 16:9 and screenshots (export from live page)

## GameDistribution
- Upload `chess-puzzles-gd.zip` (contains only index.html).
- Game runs fullscreen-responsive; SDK auto-loads on gamedistribution domains.

## itch.io
- Upload zip (rename to chess-puzzles.zip), mark "This file is playable in
  browser", entry file: index.html, viewport: fits any size (canvas scales),
  kind: html.
- Pricing: $0 (donations optional)
