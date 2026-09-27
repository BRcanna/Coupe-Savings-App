# Coupe Savings App

Coupe Savings App is a responsive coupon-trip planning prototype for local household shopping.

It turns meal-planning templates and custom shopping items into a savings-focused multi-store route. The interface demonstrates:

- Editable shopping lists and planning templates
- Exact-item matching before optional substitutions
- Store-by-store price and unit-price comparisons
- Coupon, sale, digital-offer, expiration, and stacking metadata
- One-store versus maximum-savings multi-store routing
- Source links and redemption guardrails
- Upcoming sale alerts that can be watched or muted
- Daily, weekly, monthly, yearly, and five-year budget views
- Long-term household goals with progress tracking and quick savings deposits
- Pantry status tracking between trips
- Item-level target-price watches with retailer comparisons
- Savings history with weekly momentum and annualized projections
- Optional one-time automatic routing of reviewed trip savings into a selected goal
- A colorful cartoon coupon coach advisor based on the household reference portrait
- Black, yellow, lime, orange, hot pink, and purple visual branding
- Three switchable color moods: Black + Yellow, Orange + Lime, and Pink + Purple
- Full Coupe Savings wordmark and compact app icon for browser, home-screen, and sidebar use
- A retailer adapter boundary for Walmart, Price Chopper, Market Basket, Ocean State Job Lot, Family Dollar, Dollar General, BJ's Wholesale, and Big Y

## Run locally

This is a buildless static site. From the published Site checkout, serve the `dist` directory with any static server. The GitHub repository upload keeps the page at the repository root, so serving the repository root works there.

```powershell
# Site checkout
python -m http.server 4173 --directory dist

# GitHub repository upload (root index.html)
python -m http.server 4173
```

The app uses local browser storage for household budget preferences, alert subscriptions, goal progress, pantry status, price watches, and the optional auto-save rule. The current UI uses clearly labeled illustrative preview data. Live coupon and price adapters should only use public, permitted, or approved sources and should attach source URLs, timestamps, expiration data, eligibility, and confidence metadata.
