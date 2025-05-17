# Clearance Deal Scanner Suite (US + UK) > In Progress

Python-based scanning toolkit for identifying hidden, offline, or mispriced clearance deals at major retail chains. Built for sourcing deeply discounted items (e.g., $0.01 Home Depot finds, Amazon Warehouse markdowns), this tool targets overlooked opportunities using legal automation and live-location filtering.

---

## Supported Retailers

- 🇺🇸 Home Depot (US)
- 🇺🇸 Lowe’s (US)
- 🇺🇸 Amazon.com (Warehouse Deals)
- 🇬🇧 Amazon UK (Open Box + Mispriced)
- 🇬🇧 B&Q (Coming soon)
- 🇬🇧 Screwfix / Toolstation (Scouting)

---

## Features

- Store ID / ZIP code based filtering
- Deal threshold targeting (e.g., items < $5 or < 90% MSRP)
- Markdown logs + image receipts
- Modular script support (one scanner per retailer)
- Output to CSV / logs / CLI
- Location-ready expansion (UK/EU coming soon)

---

## Project Structure

```bash
clearance-scanner-suite/
├── src/
│   ├── home_depot.py
│   ├── lowes.py
│   ├── amazon_us.py
│   ├── amazon_uk.py
│   ├── bnq_uk.py
│   └── utils.py
├── assets/
│   └── deal_proof_photos/
├── logs/
│   ├── us_runs.md
│   └── uk_runs.md
├── requirements.txt
├── .env.example
└── README.md
```
---

## Development Roadmap

See [`TO-DO.md`](https://github.com/tnauckunas/store_clearance-scanner/blob/711281156b5c5eb2018577b8b1ab8c02b9b4d6e5/TO-DO.md) for active tasks, Udemy course references, and sprint progress log.

---

_Last Updated: May 2025_
