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
│   ├── clearance_photos/
│   └── learning_log.md
├── requirements.txt
├── .env.example
└── README.md
```
---

## Development Roadmap

See [TO-DO.md](https://github.com/tnauckunas/store_clearance-scanner/blob/ebc46e020b8c6aae7f7539dca761b3b05e8b59be/TO-DO.md) for active tasks, Udemy course references, and sprint progress log.  

See [learning_log.md](https://github.com/tnauckunas/store_clearance-scanner/blob/f922a4fbef38489808996928fb1dcce9dcefd00f/logs/learning_log.md) for daily study notes, experiment tracking, and lessons learned.

---

_Last Updated: May 2025_
