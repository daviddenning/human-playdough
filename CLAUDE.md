# Human Play-dough

A browser-based drama randomiser tool for Welcome Youth, a youth group at Welcome Church, Woking. Built as a single HTML file (`index.html`), deployed via GitHub Pages.

**Live URL:** https://daviddenning.github.io/human-playdough

## What it does

Randomly pairs an item with a place to generate a scene prompt for drama games (e.g. "Washing Machine in a Swimming Pool"). Users can customise the lists before playing.

## Features

- **Setup screen** — editable lists of items and places, one field per item, with placeholder text in grey
- **Add / delete / edit** — items and places can be changed before playing
- **BEGIN button** — transitions from setup mode to randomiser mode
- **RANDOMISE button** — shuffles through options and lands on a random item + place combination; also triggered by the spacebar
- **Welcome Church branding** — black and red colour scheme, church logo, animated background image with slow fade effect

## Technical notes

- Everything lives in one file: `index.html` (HTML structure + CSS styles + JavaScript behaviour)
- No build tools, frameworks, or dependencies — opens directly in a browser
- Deployed via GitHub Pages from the `main` branch

## About the user

David is a complete beginner with no coding experience.

- Always explain technical concepts in plain English with a real-world analogy
- Build the simplest version first
- Warn before making any change that could go wrong or be hard to reverse
- At the end of each session, summarise: what we built, the key concept behind it, and a suggested next step
