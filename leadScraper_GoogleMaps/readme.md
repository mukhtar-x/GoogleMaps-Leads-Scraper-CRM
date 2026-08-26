# Lead Finder & Pipeline CRM Scraper 🚀

An automated Google Maps scraper and lead intelligence engine built with Node.js, Express, and Playwright. It extracts local business listings, audits their websites, and maps actionable software/agency service recommendations directly into a CSV-backed dashboard interface.

---

## ✨ Features

* **Smart Google Maps Scraping**: Extracts business names, categories, ratings, review counts, phone numbers, addresses, and Google Maps profile URLs.
* **Resilient DOM Handling**: Avoids detached handle errors by executing DOM operations directly within browser contexts.
* **Automated Website Auditing**: Scrapes business sites to detect email addresses, missing phone numbers, tech stacks, and social media links.
* **Service Recommendation Engine**: Analyzes sites for missing presence, non-responsive viewport settings, insecure HTTP protocols, legacy copyright footers, or slow response times to generate pitch offers (e.g., *Website Redesign*, *SSL Migration*, *CRM Automation*).
* **Interactive Lead Dashboard**: Web interface for triggering scrapes, viewing lead pipelines, and tracking statuses.

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Scraping & Automation**: Playwright (Chromium)
* **HTML Parsing & Auditing**: Axios, Cheerio
* **Data Storage**: CSV / JSON

---

## 🚀 Getting Started

### Prerequisites

* Node.js (v18+ recommended)
* npm

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/lead-scraper-dashboard.git](https://github.com/your-username/lead-scraper-dashboard.git)
   cd lead-scraper-dashboard
