# b7h30 // gear

Static site listing the actual hardware, stream gear, and training resources I use.

**Live:** https://gear.b7h30.com/

## Sections

- **Cyber Training** — Hack The Box and TCM Security Academy
- **Stream Gear** — mic, keyboard, monitors, stream deck, camera, lighting
- **Merch** — link to the Fourthwall shop
- **Desktop PC** — daily driver build
- **Proxmox Server** — homelab VM host

## Run locally

```bash
./start.sh
```

Serves the page at `http://localhost:3005/`.

## Stack

Pure static HTML/CSS — no build step, no framework. Hosted on GitHub Pages, fronted by Cloudflare DNS.

## Bot commands

PainfulBot exposes shortcuts to this site:

- `!gear` — full page
- `!training` — jumps to training section
- `!setup` — jumps to stream gear
- `!lab` — jumps to Proxmox server
- `!merch` — links to Fourthwall shop

## Affiliate disclosure

Amazon links use Amazon Associates affiliate tags. HTB and TCM links are referral links. Prices are unchanged for the buyer; I earn a small commission on qualifying purchases.
