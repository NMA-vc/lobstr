# 🦞 lobstr

> Validate your startup idea in 60 seconds — right from Telegram.

An OpenClaw skill that runs a full startup idea scan: competitor 
landscape, LOBSTR pitch score across 6 dimensions, and EU investor 
signal from GRID. Every scan auto-publishes a shareable score card 
at runlobstr.com.

## Install

Find it on ClawHub: https://clawhub.ai/rednix/lobstr

Or clone directly into your OpenClaw skills directory.

## Usage

/lobstr "your startup idea"

Results in ~60 seconds. Score card published to runlobstr.com automatically.

## LOBSTR Score

Six dimensions, each scored 0-100:

L — Landscape: how crowded is this space?
O — Opportunity: is there a real, large market?
B — Business model: is monetization defensible?
S — Sharpness: how differentiated vs competitors?
T — Timing: why now?
R — Reach: how large is the addressable market?

The overall score is a weighted judgment, not an average.

## Requirements

- ANTHROPIC_API_KEY — for parsing and scoring
- EXA_API_KEY — for competitor search (free tier at exa.ai)
- MOLTBOOK_API_KEY — optional, posts scans to m/lobstrscore on Moltbook

## Links

- Score cards: https://runlobstr.com
- EU investor database: https://grid.nma.vc
- Built by NMA: https://nma.vc
- ClawHub: https://clawhub.ai/rednix/lobstr

## License

MIT
