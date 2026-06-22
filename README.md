# Perbrain

Personal brain who keeps learning.

## What It Is

MindAI is a **browser-native reasoning engine** that lives in a single HTML file. It fetches real data from free public APIs, extracts concepts, builds a knowledge graph, and learns over time.

## Features

- **Real internet fetch** — queries Wikipedia, DuckDuckGo, Reddit, and Hacker News
- **Knowledge graph** — extracts concepts, relations, and insights from everything it reads
- **Persistent brain** — all learning stored in localStorage (your data never leaves your device)
- **Zero servers, zero API keys** — uses only free, public APIs
- **Export/Import** — download your brain as JSON, share or backup

## How To Use

Open index.html in any modern browser. No installation required.

## Tech Stack

- Single HTML file with inline CSS + JS
- Wikipedia REST API
- DuckDuckGo Instant Answer API
- Reddit JSON API
- HN Algolia API

## What Was Fixed

The original file was broken — it contained a hybrid merge of MindAI (browser reasoning engine) and SEOEngine (SEO tool) with missing JavaScript functions. Now it's:
- Self-contained (no external CSS/JS dependencies)
- Fully functional (all referenced JS functions implemented)
- Actually fetches from the internet

## License

MIT
