# Kenya Carbon Project — Benefit-Sharing Calculator

An tool for computing mandatory benefit-sharing obligations, government levies, and net developer revenue for carbon projects registered under Kenyan law.

**→ [Open the Calculator](https://steff-ojee.github.io/kenya-carbon-calculator/kenya-carbon-calculator.html)**

---

## What This Tool Does

Kenya's **Climate Change (Carbon Markets) Regulations, 2024** (Legal Notice No. 84) established a detailed framework for how revenue from carbon projects must be distributed between project developers, local communities, and the government. The rules vary depending on project type, land tenure, and whether credits are being sold internationally.

This calculator lets you input your project's financial details and instantly see:

- **Community benefit-sharing obligation** — the minimum percentage of earnings that must go to communities under a Community Development Agreement
- **Climate Change Fund levy** — the government's share of earnings for non-land-based projects
- **Issuance fees** — per-credit fees paid to NEMA upon each sale
- **Corresponding Adjustment fees** — the cost of Article 6.2 authorisation for international ITMO transfers
- **Net developer revenue** — what remains after all obligations are met

---

## The Regulatory Logic

| Provision | What It Governs |
|---|---|
| Regulation 2 | Definitions — land-based vs non-land, aggregate earnings |
| Regulation 29(a) | 40% community benefit-sharing for land-based (public/community land) projects |
| Regulation 29(b) | 25% community benefit-sharing for non-land-based projects |
| Regulation 29(3) | Exemption from community sharing for private land projects |
| Regulation 30(b) | 25% of aggregate earnings to Climate Change Fund (non-land projects) |
| Regulation 30(a) | 50% of Corresponding Adjustment fees to Climate Change Fund |
| Second Schedule | Issuance fees: USD 0.10/credit (first 15,000 tCO₂e), USD 0.20/credit above |
| Second Schedule | Corresponding Adjustment fee: USD 4.00 per ITMO transferred internationally |
| Second Schedule | Application fees: KES 10,000 (citizen) / KES 100,000 (non-citizen) |
| Second Schedule | PDD fees: KES 100,000 (citizen) / KES 200,000 (non-citizen) |

**Key concept — Aggregate Earnings:** All benefit-sharing percentages apply to aggregate earnings (gross revenue less cost of doing business), not gross revenue.

---

## What Is an ITMO?

An **Internationally Transferred Mitigation Outcome (ITMO)** is a carbon credit formally authorised by the Kenyan government for transfer to a foreign country under Article 6.2 of the Paris Agreement. Kenya applies a corresponding adjustment — removing the credit from its national accounting to prevent double-counting. Kenya has signed bilateral Article 6.2 framework agreements with Switzerland and Sweden.

---

## Limitations

This tool models regulatory obligations only. It does not model upfront project development costs, third-party verification and audit fees, carbon standard registry fees (Verra, Gold Standard, etc.), or broker fees.

---

## Related Work

- [Kenya GHG Dashboard](https://steff-ojee.github.io/Kenya-GHG-dashboard/) — national greenhouse gas data visualisation built on Kenya's Biennial Transparency Report (2024)

---

## Author

Built by **Stephanie Ojee** — Environmental Economist, Carbon Markets & ESG Advisory, Kenya.

---

*This tool is for indicative purposes only and does not constitute legal or financial advice.*
