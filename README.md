# Monday.com Stock Tax Calculator

A modern, responsive web app to estimate taxes and net value for Monday.com (MNDY) stock options.

## Features
- Real-time MNDY stock price (auto-updating, with fallback and manual override)
- 30-day price reference
- Tax breakdown (income and capital gains)
- USD/NIS currency conversion
- 12% tax return toggle (reduces income tax rate from 62% to 50%)
- Manual stock price input (overrides live price if filled)
- Responsive, mobile-friendly UI
- Interactive TradingView stock chart (toggleable)
- Quick link to trade MNDY on mndy.trade

## Usage
1. Enter the number of stocks to sell.
2. Optionally, enter a manual stock price to override the live price.
3. Choose your preferred currency (USD or NIS).
4. (Optional) Toggle the 12% tax return for a reduced income tax rate.
5. View the tax breakdown and net value instantly.
6. Use the chart toggle to view historical prices.
7. Click the trade button to open mndy.trade.

## Tech Stack
- HTML, CSS, JavaScript (single file, no build step)
- TradingView widget for price chart

## Project Structure
- `mndy_calculator.html` — Main app file
- `project_context.txt` — Project planning and context

## Notes
- All calculations are client-side and instant.
- Manual price input takes precedence over the live price if filled.
- The 12% tax return toggle is visually integrated with the currency switch.
- The UI is styled with Monday.com's color palette and Figtree font.

## License
MIT