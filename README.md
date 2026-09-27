# Coupe Savings App

Coupe Savings App is a responsive coupon-trip planning prototype for local household shopping.

It turns meal-planning templates and custom shopping items into a savings-focused multi-store route. The interface demonstrates:

- Editable shopping lists and planning templates
- Exact-item matching before optional substitutions
- Store-by-store price and unit-price comparisons
- Coupon, sale, digital-offer, expiration, and stacking metadata
- One-store versus maximum-savings multi-store routing
- Source links and redemption guardrails
- A retailer adapter boundary for Walmart, Price Chopper, Market Basket, Ocean State Job Lot, Family Dollar, Dollar General, BJ's Wholesale, and Big Y

## Run locally

This is a buildless static site. Serve the `dist` directory with any static server, then open the root page.

```powershell
python -m http.server 4173 --directory dist
```

The current UI uses clearly labeled illustrative preview data. Live coupon and price adapters should only use public, permitted, or approved sources and should attach source URLs, timestamps, expiration data, eligibility, and confidence metadata.
