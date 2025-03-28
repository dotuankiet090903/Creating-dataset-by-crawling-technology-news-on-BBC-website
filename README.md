# Technology BBC News Summarization
## Project Goal
The goal of this project is to create a summarized dataset from technology-related news articles on the BBC News website. This summarized data can serve as ground truth or improve model training efficiency in NLP tasks.

### Data Collection Process
- Crawling Method: We extract news articles using web scraping.

- Tools Used:

    - requests → Sends HTTP requests to fetch web pages.

    - BeautifulSoup → Parses and extracts content from HTML.

## Summarization Approach
- Model Used: We utilize Flan-T5 (base), a pre-trained transformer model specialized in text summarization.

- Purpose: The generated summaries help in:

    - Providing high-quality training data.

    - Reducing processing time for NLP models.

    - Enhancing model efficiency and performance.

## Dataset Overview
The dataset after created consists of two parts:

- Content – The original, unprocessed news articles.

- Summarization – The condensed version generated using Flan-T5.

## Conclusion
This project creates a structured, high-quality dataset that can be used for NLP tasks such as:

- Training summarization models.

- Improving data efficiency in machine learning.

- Serving as a benchmark for evaluation.
