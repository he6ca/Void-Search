# VoidSearch

A single-file, client-side OSINT toolkit for running lookups from your browser, using a dark, sidebar-driven console.

Made by **Heaven** · [t.me/he6ca](https://t.me/he6ca)

---

## What it does

- Runs phone, username, email, and name lookups from one sidebar
- Groups tools into Modes (Phone, Username, Email, Name) and Intelligence modules (OSINT, AI, Tor OSINT, Scanner, GEOINT, Terminal, Notes, Psych, HUMINT, Social, Result Fork, Web Recon, Database)
- Web Recon provides quick-launch links for WHOIS, DNS, SSL, headers, tech stack, and Wayback Machine lookups
- Social Networks includes a category tree modeled on the OSINT Framework
- Discord OSINT lookups
- CLI tool setup panels with guidance for installing supporting tools
- Local-only sessions: nothing is stored or transmitted

Everything runs in one HTML file, about 10,700 lines long. There is no backend.

---

## Requirements

- A current version of Chrome, Firefox, or Edge
- Windows 10 or later (tested on Windows 10)
- Optional, for the CLI tool setup panels: Python 3.13 with pip

---

## Installation

No install step is needed for the core tool. Download the HTML file and open it in your browser.

---

## Usage

1. Download `[filename].html` from this repository.
2. Open it in your browser.
3. Pick a mode or module from the sidebar.
4. Enter your query and review the results.

---

## How it works

**Frontend.** The HTML, CSS, and JavaScript are all in one file. Nothing is loaded from a server, and no build step is needed.

**Lookups.** Many lookups link out to third-party services, so results depend on those services and their availability.

**Session.** Sessions are client-side only. Closing the tab clears the session, and nothing is saved to disk or sent to a server.

---

## Security notes

- The tool runs locally in your browser and has no backend, so your queries are not sent to a server operated by the tool.
- Queries you run through third-party links are subject to those services' own privacy policies.
- Keep the HTML file in a location you control, and only open copies you trust.

---

## Limitations

- Lookups depend on third-party services, so results may be incomplete, outdated, or unavailable.
- Some features, such as the CLI tool setup panels, depend on tools installed on your own system.
- No login or account system.

---

## Project structure

```
[VoidSearch].html    # the entire tool
README.md
```

---

## Disclaimer

VoidSearch is intended for security researchers, journalists, and investigators working within the law. Only use it on people, organizations, and systems you have permission to investigate. You are responsible for complying with applicable laws and platform terms of service.
