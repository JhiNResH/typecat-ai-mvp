# TypeCat AI MVP

A tiny browser prototype for a cute typing companion: a cat that reacts to your writing, then only reads the text when you explicitly ask for AI help.

## MVP thesis

Most AI writing tools feel like productivity software. TypeCat starts as a delightful emotional companion:

```text
cute desktop cat -> reacts to typing -> user smiles -> explicit Ask Cat for AI
```

## What is in this prototype

- Cute animated black cat built with HTML/CSS
- Idle, typing, thinking, excited, and sleepy states
- Paw tapping + tail speed while typing
- Eye tracking based on mouse movement
- Writing stats: words, streak, cat mood
- Explicit `Ask cat` action that generates a local simulated suggestion
- Privacy positioning: typing activity drives reactions, text analysis only happens on click

## Run locally

```bash
npm install
npm run dev
```

Then open:

```text
http://127.0.0.1:4177
```

For a no-install fallback:

```bash
python3 -m http.server 4177
```

## Product direction

This repo is intentionally a launch-demo MVP, not a finished SaaS app. The next useful steps are:

1. Make the cat visually more iconic: pixel/chonky/blinking/sleeping variants.
2. Add selected-text interaction: select text -> Ask Cat.
3. Turn the current page into a 30-second Reddit/X demo loop.
4. Only then decide between browser extension, macOS menu bar, Electron, or Tauri.
