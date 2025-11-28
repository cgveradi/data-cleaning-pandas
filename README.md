# 🦈 Shark-project


### Problem
Many young surfers, especially beginners and teenagers, enter the ocean without sufficient knowledge about marine ecosystems, shark behavior, or safe surfing practices.

### Objective
Evaluate the real level of shark-incident risk among teenagers (ages 12–20) in the USA, and determine whether recreational activities such as surfing pose a significant danger.  
Additionally, use the data to support the development of safe, educational, and well-informed youth surf programs.

### Hypothesis
“Among ocean activities practiced by teenagers, surfing presents the highest relative risk of shark incidents.”

---

## Day 1 — Data Tasks

- Loaded dataset, inspected columns, missing values, and duplicates.

### Issues & Fixes

| Column   | Issue                | Action Taken                 |
| -------- | -------------------- | ---------------------------- |
| Age      | Missing/inconsistent | Cleaned, converted to INT    |
| Activity | Inconsistent strings | Categorized into groups      |
| Date     | Stored as string     | Converted to date time        |
| Sex      | Inconsistent values  | Standardized, filled Unknown |
| Location | Missing values       | Filled "Unknown"             |

---

## Day 2 — Data Cleaning

- Standardized column names  
- Cleaned categorical values  
- Removed duplicates  
- Filled missing values (median/mode/"Unknown")  
- Created additional columns: `age_group`, `Activity_Category`, `Season`

---

## Day 3 — Aggregation & Analysis

- Filtered data to: U.S. teens 12–20, from 1950 onward  
- Aggregated:
  - Top states with incidents  
  - Top activities  
  - Age patterns  
  - Fatal vs non-fatal outcomes  
- Built pivot tables (State × Activity)

---

## Day 4 — Insights & Recommendations

- **Location Insight:** U.S. coastal states with higher teen shark incidents indicate key regions for further study or safety interventions.  
- **Activity Insight:** Surfing shows higher involvement in teen-related shark incidents compared to other activities.  
- **Target Age Insight:** Teenagers (12–20) display distinct behavioral and activity patterns relevant to ocean safety.  
- **Fatality Insight:** Most incidents are non-fatal, but emergency preparedness should still be emphasized.  
- **Combined Insight:** State × Activity patterns help identify where educational or safety efforts may be most beneficial.

---

## Outcome

The analysis provides a clear, data-driven understanding of shark incident risks among teenagers and supports the design of safer, well-informed youth surf and ocean-activity programs through:

- Evidence-based insights  
- Improved safety protocols  
- Targeted educational strategies  
- Structured risk assessment  