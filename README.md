# 📊 Advertisement Placement & Campaign Effectiveness Analysis

## 📌 Project Overview
This project analyzes user engagement data to determine:
1. **Optimal time slots** for placing advertisements.
2. **Effectiveness of a marketing ad campaign** using control and test user groups.

The analysis is based on the provided dataset, using **Python** for data cleaning, processing, visualization, and statistical evaluation.

---

## 🎯 Business Goals
### 1. Optimal Ad Placement Time
- Identify the best time slots for maximum user engagement.
- Justify selection using trends in viewership and engagement metrics.

### 2. Evaluating the Marketing Ad Campaign
- Measure impact of ad campaign on **total viewer duration**.
- Compare **Test Group** and **Control Group** using statistical analysis.
- Decide whether the campaign should be expanded to all users.

---

## 📂 Dataset Details
- **File:** `all_stream_info.csv`
- **Key Columns:**
  - `userID` — Unique identifier for users.
  - `totalViewerDuration` — Total time (in seconds/minutes) spent watching content.
  - `timestamp` — Viewing time.
  - Other engagement metrics.

- **User Group Division** (based on last character in `userID`):
  - **Control Group:** [d, f, 1, 2, 3, 4, 5, 8]
  - **Test Group:** [a, c, b, e, 0, 6, 7, 9]

---
