# 🌊 Flood Information Extraction from FloodList Articles

This repository hosts an ongoing project focused on applying Natural Language Processing (NLP) techniques to assess flood severity in the UK using articles scraped from the FloodList website. The goal is to identify which articles contain measurable flood data (like rainfall or water level), mention flash floods, and to group them for research prioritization.

# 🧩 Workflow
1️⃣Used webscraping techniques to obtain 80 articles from FloodList website (main file: FloodList_WebScraper.ipynb).
2️⃣Load and preprocess data – Clean text, remove punctuation and stopwords (main file: 3️⃣Flood_Information_Extraction_from_FloodList_Articles.ipynb).
4️⃣Detect “flash flood” mentions – Tag articles mentioning flash floods.
5️⃣Extract information – Use regex and spaCy to pull rainfall, water levels, storm names, and locations.
6️⃣Group articles – Categorize into four types:
    FlashFlood + Numerics
    FlashFlood (no numerics)
    OtherFlood + Numerics
    OtherFlood (no numerics)
7️⃣Validate results – Manually reviewed a subset of articles to confirm accuracy (files: test_articles.csv, validated_flood_articles_summary.csv).

# 🚀📊💡 Why This Project Is Useful — and Who Can Build on It:
1️⃣ Bridges hydrology and text analytics – transforms unstructured flood reports into structured, analysable data, valuable where instrumental or open datasets are limited.
2️⃣ Helps researchers and planners prioritise – by grouping articles according to chosen keyword mentions and numerical details, it highlights which reports are most useful for follow-up, validation, or modelling.
3️⃣ Supports policy and communication research – analysts, journalists, and environmental agencies can use it to study how floods are reported, where risk narratives concentrate, and how coverage evolves over time.

# Note: This project is a work in progress. Contributions and feedback are welcome! 🤝
