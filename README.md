# Britain · Identity · Power · Memory · Narrative — British Hub

**Live site:** [justinsteinmetz.github.io/british-hub](https://justinsteinmetz.github.io/british-hub/)

A hub page for a seven-instrument interactive strand built for **Themenfeld 3 — Politics, Culture, Society: UK** (Jahrgangsstufe 11/12), Deutsche Schule Prag, English Department. Each instrument is a standalone single-file HTML tool; this page sequences them into a single argument and frames the question that runs through all seven.

> This strand is not about Britain. It's about how stories become nations.

## What this is

A single static HTML page (`british-hub-final.html`) — no build step, no dependencies beyond Google Fonts. Seven instruments move from the contemporary to the historical and back, each using a different object — political language, music, newspapers, empire, myth, physical archives — to ask the same underlying question: *who gets to tell the story, and what happens to everyone whose version doesn't survive?*

| # | Instrument | Type | Question |
|---|---|---|---|
| 01 | Who Gets to Leave? | Epistemological | Why does the same word — sovereignty — mean opposite things to different people? (Brexit, Scotland, Catalonia, Ireland) |
| 02 | British Invasion | Epistemological | If British music is built from elsewhere, what makes it British? (Wham!, The Beatles, Adele, Blues/Soul/Gospel) |
| 03 | Whose Story Is This? | Framing | When history is written, whose story survives? (Windrush, BBC, seven accounts) |
| 04 | Bassline Britain | Discovery | Why do some cultures become visible only after they've already done the work? (UK Jazz, Tomorrow's Warriors, Steam Down) |
| 05 | How British Is It? | Discovery | Why does empire keep appearing — even in things that seem entirely domestic? (Sanghera, 12 items, amnesia) |
| 06 | Who Invented England? | Epistemological | Why do some political ideas feel timeless? (Dee 1577, Burke 1790, Thatcher 1988, Brexit) |
| 07 | Who Gets to Keep It? | Archive · Capstone | If you control the evidence, do you control the story? (Benin Bronzes, Elgin Marbles, Koh-i-Noor, Rosetta Stone) |

## Design philosophy

- **Object before argument** — students encounter a specific object (a speech, an industry map, a newspaper archive, a museum object) before any analytical claim is made; the argument emerges from the encounter.
- **The same question, seven objects** — the repetition across instruments is structural, not accidental.
- **Named limitation** — the strand explicitly flags where its own framework can overreach: narrative analysis can overemphasise construction and underemphasise contingency, the moments when the story could have gone differently. The hub asks, at each instrument: *what would the framework miss here?*

## Recommended sequence

1. **Who Gets to Leave?** — opens by establishing that language itself is contested, before any historical material arrives.
2. **British Invasion → Bassline Britain** — run as a pair; both trace cultural appropriation at different scales.
3. **Whose Story Is This?** — placed after the music instruments, so students arrive already thinking about who gets credit.
4. **How British Is It? + Who Invented England?** — paired as one contemporary, one historical, both about amnesia.
5. **Who Gets to Keep It?** — closes the strand at the level of physical evidence; the hardest claim to argue around.

## Structure

```
british-hub-final.html   — single-file hub page (HTML + embedded CSS, no JS dependencies)
```

Visual style: dark editorial aesthetic (near-black ground, gold/crimson accents, Playfair Display + IBM Plex Mono), a Union Jack motif in the hero, and a capstone instrument card visually distinguished as the "spine" of the strand.

## Deployment

Hosted via GitHub Pages directly from this repo. To update, edit `british-hub-final.html` and push to the default branch — no build step required.

## Context

Part of a broader set of interactive HTML classroom instruments developed for DSP Prague's English curriculum, alongside strands such as *The Individual & Society* (IDHUB) and the Year 10 Punishment & the State unit.
