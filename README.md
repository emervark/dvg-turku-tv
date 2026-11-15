# DVG Turku – ticket price TV (9:16)

Live page for the BrightSign player at the Da Vinci Genius Turku ticket desk:
**https://emervark.github.io/dvg-turku-tv/**

- Prices, texts, special dates and holiday rules are read from the Google Sheet
  `DVG Turku – TV piletihinnad (andmed)` (cell `config!A1`) every 2 minutes.
  Edit them in the Claude artifact editor "DVG Turku — Lipputaulu 9:16", not in the sheet.
- The page itself works out weekdays, weekends and Finnish public holidays and switches at midnight.
- BrightSign: HTML5 widget with the URL above, screen orientation **Portrait** (1080×1920).
- Test a date: `https://emervark.github.io/dvg-turku-tv/#d-2026-12-24`
