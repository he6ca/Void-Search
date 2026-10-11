# VoidSearch

Made by Heaven.

A client-side OSINT toolkit that runs entirely in your browser. VoidSearch ships as a single HTML file, so there's no backend, no account, and no server that sees your queries.

## Features

- **Dashboard** with a sidebar-driven layout for switching between tools
- **Search modes:** Phone, Username, Email, and Name lookups
- **Intelligence modules:** OSINT, AI, Tor OSINT, Scanner, GEOINT, Terminal, Notes, Psych, HUMINT, Social, Result Fork, Web Recon, and Database
- **Web Recon:** quick-launch links for WHOIS, DNS, SSL, headers, tech stack, and Wayback Machine lookups
- **Social Networks:** a category tree modeled on the OSINT Framework
- **Discord OSINT** lookups
- **CLI tool setup panels** with guidance for installing supporting tools
- **Local-only sessions:** nothing is stored or transmitted

## Requirements

- **Browser:** a current version of Chrome, Firefox, or Edge
- **Operating system:** Windows 10 or later (tested on Windows 10)
- **Optional, for CLI tool setup panels:** Python 3.13 with pip

## Getting Started

1. Download `[filename].html` from this repository.
2. Open it in a modern browser (Chrome, Firefox, or Edge).
3. Pick a mode from the sidebar and start searching.

No build step or dependencies are required for the core tool.

## Architecture

VoidSearch is a single, self-contained HTML file of roughly 10,700 lines. All logic runs client-side. Lookups link out to third-party services, so results depend on those services.

## Responsible Use

VoidSearch is intended for security researchers, journalists, and investigators working within the law. Only use it on people, organizations, and systems you have permission to investigate. You are responsible for complying with applicable laws and platform terms of service.

## Contact

DM: t.me/he6ca
