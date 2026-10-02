AIR WATCH — DEPLOYMENT NOTES
============================

File to publish:
  air-watch-index.html

For a public link, rename the file to index.html and deploy it to any static web host.

Option A — Netlify Drop (fastest)
1. Rename air-watch-index.html to index.html.
2. Go to Netlify Drop / Netlify's manual deploy page.
3. Drag index.html onto the deploy area.
4. Netlify gives you a public HTTPS URL you can share.

Option B — GitHub Pages
1. Create a public GitHub repository, e.g. air-watch.
2. Upload the file as index.html.
3. Open repository Settings > Pages.
4. Deploy from the main branch / root folder.
5. Share the resulting github.io URL.

How it works
- Browser calls Open-Meteo Air Quality API directly; no API key is stored.
- Current US AQI, PM2.5, PM10, ozone and NO2 are shown.
- 12-hour US AQI forecast is charted.
- Page refreshes automatically every 5 minutes, plus a manual refresh button.
- City coordinates are embedded for Singapore, Kuala Lumpur and Ipoh.

Important
- Open-Meteo data is modeled from CAMS forecasts. It is not the official Singapore PSI or Malaysia DOE/APIMS station reading.
- Public-host availability and API usage are subject to the respective providers' terms and uptime.
