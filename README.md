# Quiro Pitch Deck

Single-page HTML pitch deck styled with Tailwind CSS, using Font Awesome icons and Chart.js for interactive charts.

## Files
- `index.html`: Main pitch deck page

## Requirements
- Internet connection (CDNs: Tailwind, Google Fonts, Font Awesome, Chart.js)
- Modern browser (Chrome, Edge, Firefox, Safari)

## How to Run
- Double-click `index.html` to open in your browser, or
- Serve locally for consistency:
  - PowerShell (Windows):
    ```powershell
    cd "C:\Users\USER\.cursor\Quiro_pd"
    python -m http.server 8080
    ```
  - Visit `http://localhost:8080/index.html`

## Print to PDF
- Use browser Print
- Portrait, enable background graphics, choose A4 or Letter
- Print styles are included in the page

## Troubleshooting
- Charts not showing:
  - Ensure you are online (CDNs must load)
  - Open DevTools (F12) → Console for JS errors
  - Try the local server approach above
- Fonts/icons missing: verify access to Google Fonts and Cloudflare CDNs

## Customize
- Edit content and colors in `index.html`
- Chart data/options are in the bottom `<script>` block

## License
Proprietary. All rights reserved.
