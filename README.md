# Mini LCA – Textile Peru to Italy

This project calculates the carbon footprint of one textile garment manufactured in Peru and transported to Italy.

## Methodology
- Functional unit: 1 garment
- Based on GHG Protocol logic
- DEFRA 2025 Condensed Conversion Factors applied
- Transport calculated using tonne-km

## Scenarios analyzed
1. Baseline (Sea freight + conventional cotton)
2. Air freight
3. Recycled cotton

## Key insight
Air freight increases the carbon footprint by more than 8000% compared to sea freight.

## Structure
- Mini_LCA_Textil_Peru_Italia_v1.ipynb
- mini_lca_textil_with_defra.csv

## Purpose
Educational + prototype for potential ESG supply chain consulting.
---

## Assumptions

- Cotton emission factor is a literature-based placeholder value.
- Electricity factor based on DEFRA 2025 UK grid average.
- Transport factors derived from DEFRA 2025 condensed set.
- Functional unit modeled as one shipment equivalent.

---

## Limitations

- Cotton factor does not reflect region-specific agricultural variability.
- Model excludes packaging, warehousing and retail phases.
- Electricity mix corresponds to UK grid, not Peru production mix.
- This is a screening-level LCA, not ISO 14040 certified.

---

## Strategic Insight

Transport dominates total emissions in long-distance textile trade.

In this specific Peru–Italy route, switching from sea freight to air freight increases emissions by more than 8000%.

Material substitution (e.g., recycled cotton) shows marginal impact compared to logistics decisions in this configuration.
