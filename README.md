# Word Ladder

A free single-file HTML5 word puzzle inspired by Lewis Carroll's word ladders.
Climb from the start word to the end word by changing one letter at a time —
every intermediate step must be a real English word.

Play: https://shuangyueliao.github.io/word-ladder/

## Features
- Daily Challenge (3 seeded puzzles per day) + Endless mode (Easy 3 / Medium 4 / Hard 5+)
- Smart letter keyboard: tap a letter position, only letters that form valid words are shown
- Hint system (shortest path length + one masked next word), undo, move counter with "Par"
- PERFECT x2 score for matching the shortest path, streak & best saved locally
- Ink-on-paper visual style, rising ladder card animation
- 1,400+ curated common 4-letter words, graph connectivity verified

## Tech
Single `index.html`, zero external assets, vanilla JS + CSS + WebAudio.
Platform SDKs (CrazyGames / GameDistribution) load only on their own domains.
