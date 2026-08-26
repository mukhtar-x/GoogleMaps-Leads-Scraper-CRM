# LeadScrapers 🛠️

A centralized collection of automated lead generation tools, web scrapers, and intelligence extraction engines designed to discover, audit, and analyze potential client leads.

---

## 📁 Repository Structure

```text
LeadScrapers/
├── leadScraper_GoogleMaps/     # Google Maps scraper & website auditing dashboard
└── .gitignore
```

---

## 🚀 Available Scrapers

### 📍 1. Google Maps Lead Scraper (`leadScraper_GoogleMaps`)

An end-to-end scraper and lead intelligence dashboard built with Node.js, Express, and Playwright.

* **Google Maps Data Extraction**: Pulls business names, phone numbers, ratings, review counts, categories, and locations.
* **Automated Website Auditing**: Scrapes target websites for email addresses, phone numbers, tech stacks, and social media links.
* **Service Recommendation Engine**: Evaluates website issues (e.g., missing SSL, non-responsive layouts, legacy copyright footers, slow response times) and suggests specific agency offerings like *Website Redesign*, *SSL Migration*, or *CRM Lead Automation*.
* **Interactive Dashboard**: Full UI to trigger scraping runs and manage CSV-backed lead pipelines.

---

## ⚡ Quick Start

### Prerequisites

* Node.js (v18 or higher)
* npm

### Running a Scraper

1. Clone the repository:
   ```bash
   git clone [https://github.com/mukhtar-x/LeadScrapers.git](https://github.com/mukhtar-x/LeadScrapers.git)
   cd LeadScrapers
   ```

2. Navigate to the desired scraper module:
   ```bash
   cd leadScraper_GoogleMaps
   ```

3. Install dependencies:
   ```bash
   npm install
   npx playwright install chromium --with-deps
   ```

4. Launch the application:
   ```bash
   npm start
   ```

5. Open `http://localhost:3000` in your browser.

---

## ⚙️ Deployment

Modules with web dashboards (such as `leadScraper_GoogleMaps`) can be deployed directly as a **Web Service** on platforms like Render or Railway:

* **Build Command**: `npm install && npx playwright install-deps chromium`
* **Start Command**: `npm start`

---

## 📄 License

This repository is maintained for internal agency lead generation workflows.
