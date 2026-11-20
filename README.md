# Forest Fire Management System – Amrabad Tiger Reserve

A single-page website for exploring forest fire records of Amrabad Tiger Reserve (Telangana Forest Department).

Open `index.html` in a browser, or view it on GitHub Pages: https://atrdbms.github.io/forest-fire/

## Features
- Filters: Year, Month, Division, Range, Section, Beat, Fire occurred, Reason
- Dashboard with charts (month, year, reason, range, daily, beats, sections)
- Satellite map (Google Satellite / Hybrid / Terrain, Esri imagery) with fire points, heat map and KML / KMZ / GeoJSON upload
- Fire occurrence table with search, sort and CSV / Excel download
- Reason-wise analysis
- Reports (range, section, beat, month, reason, daily register, officer-wise) with print / PDF / Excel / CSV

## Data
Data comes from the FFMIS Google Sheet (tab `FFMS-details`). The site syncs with the sheet automatically when opened and every 5 minutes (the sheet must be shared as "Anyone with the link can view"). If the sheet cannot be reached, the saved copy bundled in the page is shown.
