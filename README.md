# Stave Invaders 

A browser-based grand staff sight-reading trainer. A whole note appears on either the treble or bass staff — name it before time runs out.

**[Try it live →](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/note-trainer.html)**
*(replace with your actual GitHub Pages URL — see [Deploying](#deploying-to-github-pages) below)*

## Features

- **Grand staff** — treble and bass clef shown together, joined by a brace, just like real notation
- **Extended range** — ledger lines up to 2 lines above and below each staff
- **Keyboard shortcuts** — answer with `Q W E R T Y U`, mapped to the notes `C D E F G A B`, or tap the on-screen keys
- **Adjustable session length** — 30s / 60s / 120s
- **Clef modes** — practice treble only, bass only, or both (randomized)
- **Scoring** — `score = notes correct × accuracy`, so both speed and precision count
- **Mobile-friendly** — layout scales down for small screens

## How to play

1. Vistt `https://ben-razor.github.io/stave-invaders/` or `note-trainer.html` in any modern browser.
2. Choose a clef mode and duration, then hit **Start Practice**.
3. A note appears on one of the two staves (the other dims slightly so it's clear which one is active).
4. Name the note — click a key or press its keyboard shortcut — before time runs out.
5. Your score, correct count, and accuracy are shown live and summarized at the end.

## Tech

No dependencies, no build step — just a single static HTML file using inline SVG for the staff notation.