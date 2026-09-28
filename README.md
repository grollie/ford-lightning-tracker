# Ford F-150 Lightning Watch

A daily-updated dashboard tracking Ford F-150 Lightning listings.

- **Alert list**: mileage under 20,000, Pro Power Onboard, no reported accidents, priced under $40,000.
- **Price tracker**: same criteria, priced at $55,000 or below, with day-over-day price movement.

`data.json` is refreshed once a day by a scheduled agent that searches AutoTrader, Cars.com, CarGurus, TrueCar, and CarMax. `index.html` is a static page that reads `data.json` at load time — open it directly or serve it via GitHub Pages.

Listing details (mileage, Pro Power, accident history) are as reported by the source site and are not independently verified.
