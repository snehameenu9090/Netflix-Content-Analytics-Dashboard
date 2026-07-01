# Netflix-Content-Analytics-Dashboard

## 📌 Project Overview
This project delivers a comprehensive Exploratory Data Analysis (EDA) on Netflix's content catalog. The main objective is to understand content distribution patterns (Movies vs. TV Shows), trace historical release trends, analyze global production hubs, and extract actionable content acquisition insights for streaming platforms using core Python libraries.

## 🛠️ Tools & Technologies Used
As aligned with the 2026 industry curriculum guidelines, the following core technologies were used:
- **Programming Language:** Python 3.12+
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** VS Code / Terminal Scripting Mode

## 📋 Curriculum Deliverables Achieved

### 1. Data Loading & Catalog Auditing
- Formulated a multi-variable unstructured Netflix catalog dataset including `show_id`, `type`, `title`, `country`, `release_year`, `rating`, `duration`, and `listed_in`.
- Examined structural data metrics, shape profiles, and data types across all rows.

### 2. Advanced Data Preprocessing & Feature Engineering
- Identified and removed duplicate content records based on multi-column subsets (`title`, `type`, `release_year`) to ensure absolute data integrity.
- **Feature Engineering:** Built a robust data transformation system using lambda expressions to parse duration strings (`min` or `Seasons`) and convert them into standardized numeric minute values (`duration_numeric`).

### 3. Exploratory Data Analysis (EDA)
- Extracted exact content portfolio share between Movies and TV Shows.
- Isolated leading production sovereign geo-hubs using value frequency metrics.
- Tracked temporal growth patterns over release years to evaluate archive expansion strategies.

### 4. Advanced Visualization Pipeline
Generated clean and professional analytical charts to visualize global streaming trends:
1. **Portfolio Content Share:** High-contrast Pie Chart for Movies vs. TV Shows split.
2. **Geographic Distribution:** Order-sorted Count Plots for content hubs.
3. **Temporal Content Growth:** Linear Trend Plots for release years.
4. **Duration Bandwidth Spreads:** Multi-variable Stacked Histograms with KDE lines.
5. **Consumer Safety Layout:** Rating Density Horizontal Bar Plots.

---

## 📈 Strategic Content Insights & Executive Summary
Based on the data output, the following analytical observations have been documented for streaming platform business strategy:
1. **Catalog Composition:** While Movies currently dominate the overall volume, TV Shows provide much heavier cumulative runtime engagement per asset due to extensive seasonal formats.
2. **Sovereignty Production Hubs:** The USA and India stand out as primary content creation pillars, making them the most critical target regions for future localization investments.
3. **Archival Modernization:** Content published after 2015 shows an aggressive exponential hockey-stick growth curve, shifting licensing strategies toward modern digital-first originals over historical assets.

