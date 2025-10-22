# Chipotle Shares Outstanding

This web page fetches and displays the maximum and minimum shares outstanding for Chipotle Mexican Grill from SEC XBRL data.

**Features:**
- Fetches JSON data for CIK 0001058090 or specified via URL parameter
- Shows entity name, max, and min shares with fiscal year
- Supports changing company via `?CIK=` query parameter

**Usage:**
- Open index.html in a browser.
- To specify a different CIK, add `?CIK=XXXXXXXXXX` to the URL.

**Note:** Data is fetched directly from SEC, with proxy to avoid CORS issues.
