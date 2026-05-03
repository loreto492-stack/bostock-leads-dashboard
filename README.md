# Bostock Leads Dashboard

Single-file HTML dashboard for tracking Bostock Pools & Spas leads, plus monthly Google Ads and Facebook/Instagram Ads performance.

**Live URL:** https://loreto492-stack.github.io/bostock-leads-dashboard/

## What it does

- Imports lead data from monthly Excel workbooks
- Auto-categorises lead status (Current Leads, Building a Pool, Follow Up Leads, No Follow Up, Appointment Booked)
- Monthly and yearly charts, year-over-year comparison, source/location breakdowns
- Inline editing of any lead's status, category, source, location
- Manual entry of monthly Google Ads metrics (clicks, impressions, cost, conversions)
- Manual entry of Facebook/Instagram Ads metrics across three campaign types: Lead Generation, Website Traffic, Instagram Followers
- One-click PDF export for monthly reporting
- Backup / Restore data to a JSON file

## How data is stored

All data lives in your browser's `localStorage` — nothing is sent anywhere. Each device/browser has its own data store. Use **Backup** to download a JSON file you can restore on another computer.

## Running locally (optional)

The dashboard is just one HTML file. Either:

- Open it via the GitHub Pages URL above, or
- Double-click `bostock-leads-dashboard.html` to open it directly in a browser, or
- Run the included `_server.js` for a localhost URL: `node _server.js` then visit `http://localhost:8765/`
