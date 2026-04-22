# NLP Portfolio – Web Mining & Applied NLP

**Author:** Blessing Aganaga
**Course:** Web Mining & Applied NLP

---

## 1. NLP Techniques Implemented

- **Tokenization**
  - Used in `stage03_transform_blessing.py` and `stage03_transform_case.py` to split cleaned text into tokens for analysis.

- **Text Cleaning and Normalization**
  - Applied lowercasing, punctuation removal, whitespace cleanup, and token filtering.

- **Frequency Analysis**
  - Computed token counts and top-word frequency outputs.
  - Generated:
    - `blessing_top_tokens.png`
    - `case_top_tokens.png`

- **Web Scraping / HTML Extraction**
  - Used `stage01_extract.py` to collect raw HTML content from web sources.
  - Saved raw files:
    - `data/raw/blessing_raw.html`
    - `data/raw/case_raw.html`

- **API-Based Text Processing**
  - Completed structured JSON extraction and transformation in `nlp-04-api-text-data`.

- **Visualization**
  - Created word cloud and token chart outputs for text comparison.

---

## 2. Systems and Data Sources

- **HTML Web Pages**
  - Extracted and analyzed raw website content.

- **JSON API Data**
  - Processed structured text records from APIs in Module 4.

- **Processed CSV Outputs**
  - Generated cleaned structured outputs:
    - `blessing_processed.csv`
    - `case_processed.csv`

- **Handling Messy Data**
  - Removed HTML noise and markup.
  - Standardized inconsistent formatting.
  - Filtered unnecessary punctuation and empty values.

---

## 3. Pipeline Structure (EVTL)

- **Extract**
  - Used `stage01_extract.py` to collect source data and save raw HTML files.

- **Validate**
  - Used:
    - `stage02_validate_blessing.py`
    - `stage02_validate_case.py`
  - Checked source structure and file readiness before processing.

- **Transform**
  - Used:
    - `stage03_transform_blessing.py`
    - `stage03_transform_case.py`
  - Applied tokenization, cleaning, normalization, and preparation for analysis.

- **Load**
  - Used `stage04_load.py` to save processed outputs, summaries, and visualizations.

---

## 4. Signals and Analysis Methods

- Word frequency and top-token counts
- Keyword prominence across datasets
- Vocabulary comparisons between sources
- Visual signals using charts and word clouds
- Structured CSV summaries for downstream review

Outputs included:

- `blessing_top_tokens.png`
- `case_top_tokens.png`

---

## 5. Insights

- Cleaned text produced better keyword results than raw HTML.
- Validation steps improved reliability before transformation.
- Frequency charts quickly highlighted repeated topic terms.
- Word cloud visuals made dominant themes easier to recognize.
- Repeatable pipelines made it easier to process multiple sources consistently.

A key takeaway was that structured workflows convert messy web text into useful analytical outputs.

---

## 6. Representative Work

### Project 1: NLP Pipeline
https://github.com/teflxndxn/nlp-06-nlp-pipeline

Complete EVTL workflow using staged Python scripts for extraction, validation, transformation, and loading. Best example of my repeatable NLP pipeline skills.

### Project 2: Web Documents
https://github.com/teflxndxn/nlp-05-web-documents

Focused on extracting and cleaning HTML web content using Python and BeautifulSoup. Demonstrates web mining and content extraction skills.

### Project 3: API Text Data
https://github.com/teflxndxn/nlp-04-api-text-data

Used APIs and JSON data sources for text analysis and structured outputs. Demonstrates data integration and processing skills.

---

## 7. Skills

- Python data processing
- Working with HTML, JSON, and CSV data
- Web scraping with BeautifulSoup
- Text cleaning and normalization
- Tokenization and frequency analysis
- Building repeatable EVTL pipelines
- Data validation workflows
- Creating charts and word clouds
- Professional Markdown documentation
- Communicating analytical results clearly

---

## Conclusion

This portfolio demonstrates practical experience using Python and NLP workflows to extract, clean, analyze, and present text data from multiple sources. These projects strengthened my skills in automation, analytics, and professional technical communication.
