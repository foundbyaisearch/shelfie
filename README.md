# Shelfie

**Get your products picked by AI.**

Shoppers are increasingly asking AI assistants (ChatGPT, Google AI, Perplexity, Copilot) what to buy. Shelfie shows a Shopify merchant whether their products surface in those answers, then fixes the structured product data that keeps them hidden.

This repository contains the working marketing-site prototype with a live "Ask the AI" visibility simulator.

## Live demo

If GitHub Pages is enabled for this repo, the prototype is live at:

```
https://shelfie.github.io/shelfie/
```

Or just open `index.html` in any browser. No build step, no dependencies.

## What the prototype shows

- **Ask the AI simulator**: pick a sample store, type a shopper question, and watch the AI recommend competitors while the merchant's product gets skipped, with the exact reason why.
- **AI Visibility Score**: a 0 to 100 readiness score plus an estimated monthly revenue leak.
- **Product audit**: a SKU by SKU table showing which products are invisible, half there, or showing up, with one click "Fix now" buttons.
- **Before / after**: a real example of the product data Shelfie generates.
- **Pricing**: Starter $39, Growth $99, Agency $299 per month, with a free visibility score.

> The demo uses realistic sample data so the experience can be felt without connecting a store. Production connects to the live Shopify catalog and queries real AI assistants.

## The opportunity (short version)

- 8M+ Shopify and WooCommerce stores worldwide.
- Traffic from structured product catalogs converts roughly 2x better than scraped or outdated data.
- Google launched the Universal Commerce Protocol and Microsoft launched Copilot Checkout in January 2026, making structured product data the new shelf.
- Existing AI visibility tools track brand mentions. None fix SKU level product data and feeds. That is the wedge.

## Business model

Freemium micro-SaaS. Free visibility score as the hook, paid subscription for automated data generation and ongoing monitoring. Blended ARPU target around $70 to $90 per month. Distribution via the Shopify App Store and a WooCommerce plugin.

## Tech

Single self contained `index.html`. Vanilla HTML, CSS and JavaScript. No frameworks, no API keys, nothing to install.

## Status

Prototype for visualization and validation. Not a live product.

---

Concept by House of Turnberry, 2026.
