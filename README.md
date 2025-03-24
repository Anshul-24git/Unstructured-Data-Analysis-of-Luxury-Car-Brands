# 🏎️ Entry-Level Luxury Car Market Analysis using Unstructured Data

## 📘 Assignment Overview
As analytics consultants for JD Power and Associates, we performed a competitive analysis of the entry-level luxury car market in the USA. The analysis was based on ~5000 social media posts from the Edmunds.com discussion forums. The focus was to extract insights from unstructured discussions without relying on sentiment analysis (assuming all sentiments are positive).

---

## 🧪 Tasks & Methodology

### ✅ Task A: Zipf’s Law
- **Objective**: Test if forum discussions follow Zipf’s Law.
- **Method**: Used word frequency analysis (without removing stopwords or stemming).
- **Result**: Empirical data aligns with Zipf’s Law, verified visually and econometrically.

### ✅ Task B: Brand Identification
- **Extracted top 10 brands** by:
  - Removing stopwords.
  - Mapping car models to parent brands using a lookup list.
  - Limiting brand count per post to 1 even if repeated.

### ✅ Task C: Lift Ratio Calculation
- **Purpose**: Measure co-occurrence strength of brand mentions.
- **Approach**: Lift values calculated considering word distance ≤ 7 within a post.

### ✅ Task D: MDS Map
- **Tool**: Multi-Dimensional Scaling
- **Insight**: Visualized brand similarities based on co-mentions.

### ✅ Task E: Strategic Insights from C & D
- Brands closer on the MDS map shared positioning.
- Lift ratios revealed strong brand associations and competition.

### ✅ Task F: Attribute Extraction
- **Top 5 Car Attributes**: Extracted by frequency.
- **Brand-Attribute Mapping**: Identified most associated brands per attribute.

### ✅ Task G: Strategic Advice Based on Attributes
- Provided brand-specific positioning strategies based on feature associations.

### ✅ Task H: Aspirational Brand Analysis
- **Metric**: Based on desire-related phrases (e.g., "want", "wish", "plan to buy").
- **Outcome**: Identified the most aspirational brand and its business implications.

---

## 📂 Files
- `UDA.py`: Contains all scraping, processing, and analysis scripts.
- `README.md`: This file (project summary and documentation).

---

## 🔧 Tools & Libraries
- Python 3.x
- BeautifulSoup, Requests (scraping)
- NLTK (text processing)
- Scikit-learn (MDS)
- Matplotlib (visualization)
- Pandas (data manipulation)

---

## 📈 Key Takeaways
- Zipf’s Law holds for real-world forum text data.
- Top brands show nuanced associations with features.
- Aspirational value can be data-driven, not just intuitive.
- Strategic market positioning can be guided using simple lift-based metrics and visualizations.

---

> 🚨 *Note*: This project is for academic purposes and uses publicly available data from Edmunds.com.
