# 🏎️ Analyzing Entry-Level Luxury Car Discussions Using NLP

## 📘 Project Overview
This project explores user-generated discussions from Edmunds.com forums to uncover competitive insights in the entry-level luxury car market. Using web scraping, natural language processing (NLP), and statistical analysis, the goal was to identify brand perceptions, feature associations, and consumer aspirations.

---

## 🧠 What This Project Does
- Scrapes thousands of real-world user posts from Edmunds forums.
- Validates Zipf’s Law on raw textual data.
- Extracts and ranks automotive brands based on mention frequency.
- Measures brand associations using lift ratios.
- Visualizes brand relationships using multi-dimensional scaling (MDS).
- Identifies commonly discussed car features and maps them to specific brands.
- Analyzes which brand appears most aspirational among users.

---

## 📊 Key Insights
- **Word frequencies** from organic discussions show strong adherence to Zipf's distribution.
- **Top brands** emerged based on adjusted frequency counts, mapping models to parent brands.
- **Lift ratios** revealed hidden relationships and co-mentions between competing brands.
- **MDS visualizations** provided intuitive maps showing brand proximity in consumer minds.
- **Car features** like performance, design, and reliability showed clear brand affinities.
- **Aspirational brand analysis** highlighted which brand users most frequently expressed desire to own.

---

## ⚙️ Technologies Used
- `Python 3.x`
- `BeautifulSoup`, `Requests` (web scraping)
- `NLTK` (text processing)
- `Scikit-learn` (MDS)
- `Pandas`, `NumPy` (data analysis)
- `Matplotlib` (visualization)

---

## 📂 Project Structure
- `assignment_1.py`: Core script containing all scraping, data transformation, analysis, and plotting code.
- `README.md`: Documentation and project summary.

---

## 🚀 How to Run

```bash
python assignment_1.py

---

> 🚨 *Note*: This project is for academic purposes and uses publicly available data from Edmunds.com.
