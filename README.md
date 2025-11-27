# 🦈 Sharkboy & Lavagirl Surf Camp – Shark Attack Analysis

## Scenario

Sharkboy & Lavagirl Surf Camp plans a **U.S. coastal surf school** targeting **teenagers (12–20 years)**. Goal: **safe, professional surf lessons** guided by historical shark attack data.

---

## Step 1 — Hypotheses

- **Location & Risk:** Sharks attack more in some U.S. states → choose safe locations.
- **Activity Risk:** Surfing, swimming differ in risk → plan lessons safely.
- **Demographics:** Age/gender affect attack likelihood → tailor safety campaigns.
- **Seasonality:** Shark attacks vary by month → schedule lessons accordingly.

Focus: **U.S. teenagers, low-risk locations**.

---

## Day 1 — Data Tasks

- Loaded dataset, inspected columns, missing values, duplicates.
- **Issues & fixes:**

| Column   | Issue                | Action Taken                 |
| -------- | -------------------- | ---------------------------- |
| Age      | Missing/inconsistent | Cleaned, converted to int    |
| Activity | Inconsistent strings | Categorized into groups      |
| Date     | Stored as string     | Converted to datetime        |
| Sex      | Inconsistent values  | Standardized, filled Unknown |
| Location | Missing values       | Filled 'Unknown'             |

---

## Day 2 — Data Cleaning

- Standardized columns, cleaned categories, removed duplicates.
- Filled missing values (median/mode/‘Unknown’).
- Created: `age_group`, `Activity_Category`, `Season`.

---

## Day 3 — Aggregation & Analysis

- Filtered: **U.S. teens 12–20, 1950+**.
- Aggregated:
  - Top states & activities for attacks.
  - Age patterns.
  - Pivot tables: State × Activity.
- Key outcomes: fatal vs non-fatal attacks.

---

## Day 4 — Insights & Recommendations

- **Safe Locations:** Coastal U.S. states with historically low attacks.
- **High-Risk Activities:** Surfing → implement extra safety; others low-risk.
- **Target Age:** Teenagers 12–20 → focus safety campaigns here.
- **Fatality:** Mostly non-fatal; still prepare emergency response.
- **Combined View:** Heatmap State × Activity guides operational decisions.

**✅ Outcome:** Data-driven, safe, and profitable teen surf school.
