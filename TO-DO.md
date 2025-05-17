# TO-DO: Clearance Deal Scanner Suite  
_A live development task log + learning tracker for the US/UK retail deal scraper project._

---

## Core Objectives

- [ ] Build Python CLI scraper for Home Depot, Lowe’s, Amazon US/UK, B&Q UK  
- [ ] Log each scan with markdown + screenshots (`logs/`)  
- [ ] Add `.env` support for location filtering / API keys  
- [ ] Modularize `src/` logic for future mobile or web integration  
- [ ] Add detection for: clearance, open box, unlisted pricing, hidden bundles  

---

## Web Scraping Skill Development

**Learn + Apply:**

## Udemy Courses to Pull From
Your core learning path for the Clearance Deal Scanner project (Python CLI).

---

### 1. Modern Web Scraping in Python
- Most up-to-date
- Covers `requests`, `BeautifulSoup`, `lxml`, `selenium`, anti-bot
- Focuses on modern HTML structure, pagination, structured scraping  
→ **Start with this course** to build your scanner’s skeleton.

---

### 2. Master Python Web Scraping Automation using BS4 & Selenium
- Full automation workflow (parse → store → export)
- Crucial for dynamic content (e.g., Amazon product DOM)  
→ **Study while implementing Amazon + Lowe’s**

---

### 3. Web Scraping & API Fundamentals in Python
- REST API concepts + reusable CLI-friendly logic
- Helps build flexible, multi-retailer compatible structure  
→ **Use when developing `utils.py` + CLI**

---

### 4. Web Scraping Course in Python (BS4, Selenium, Scrapy)
- Framework comparison (modular design thinking)
- Good for mid-late stage development  
→ **Use for reinforcing modularity**

---

### 5. Web Scraping with Python using Requests, lxml & Splash
- Strong for JS-heavy pages
- Introduces `Splash` (headless browser)  
→ **Use only when HTML parsing fails due to JavaScript**

---

### 6. Web Scraping in Python: BS4 + Selenium
- Covers edge cases and advanced patterns  
→ **Use as fallback or for reference overlap**

---

## Future Expansion

- [ ] Add GUI/mobile support (Tkinter → React Native)  
- [ ] Export result set to CSV / email notification  
- [ ] Optional visual heatmap for clearance intensity  
- [ ] Begin UK store reverse engineering (Boots, Tesco, Argos)  

---

_Last updated: May 2025_
