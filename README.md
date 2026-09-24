# MUVs Scoping Calculator

A single-page scoping calculator for the **Real-Time Personalization – MUVs (100K)** SKU model. Built with plain HTML/CSS/JS using Salesforce Lightning Design System styling.

## Live Calculator

**https://ebbmax.github.io/MUVs-Scoping-Calculator/**

## What it does

Walks a seller through four steps to produce a recommended SKU quantity and consumption entitlements:

1. **Scoping Context** — customer name and contract length.
2. **Channel Scoping** — Web and/or Mobile App.
3. **Channel Volumes** — average monthly unique visitors per site and monthly active users per app across the last 12 months.
4. **Recommended SKUs** — a single SKU (Real-Time Personalization – MUVs (100K)) with quantity computed as `⌈(MUVs × 12 × ContractLength) / 100,000⌉` summed across Web and Mobile, plus a Consumption Entitlements table (MUVs, Real-Time Interactions) and Additional Considerations callouts.

## Running Locally

Open `index.html` directly in a browser — no build step required.
