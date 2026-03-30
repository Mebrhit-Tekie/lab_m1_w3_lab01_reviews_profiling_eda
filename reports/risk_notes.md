# Risk Notes — Bank App Reviews (Week 3 Lab 01)

Dataset source: Google Play reviews (3 bank apps), scraped via google-play-scraper.
Raw snapshot saved: `data/raw/reviews_raw.csv`
Clean dataset saved: `data/processed/reviews_clean.csv`

## Data Quality Findings

### Missing values
- Columns with missing values: <fill>
- Action taken: Dropped rows with null or empty review_text

### Duplicates
- Duplicate rows found: <fill>
- Action taken: Dropped exact duplicates

### Date issues
- Invalid/unparseable dates: <fill>
- Action taken: Converted with `errors="coerce"`, invalid dates become NaT

## Outliers (Review Length)
- IQR outliers count: <fill>
- Z-score outliers count (`|z| > 3`): <fill>
- Manual check (top 5 longest): <fill>

## Key EDA Insights
- Insight 1: <fill>
- Insight 2: <fill>

## Recommendation
- Recommendation to Product/Support: <fill>
