# Brain Drain Analysis using Google Books Ngram

## Overview
This project analyzes the evolution of the term **“brain drain”** in published literature from 1900 to 2022 using Google Books Ngram data. The analysis compares brain drain with related concepts such as globalization, development, human capital, and skilled labor to understand changes in academic and policy discourse over time.

The project was carried out entirely using Python and is designed as a reproducible data analysis and storytelling exercise.

---

## Data Source
- Google Books Ngram Viewer (English corpus)
- Time period: 1900–2022

---

## Data Preparation
The raw data was initially obtained from the Google Books Ngram API in **JSON format**.

Using **Python**, the JSON data was parsed, cleaned, and converted into a structured CSV file (`ngram_wide.csv`) in a separate data preparation notebook.  
This cleaned CSV dataset is used as the input for the main analysis notebook in this repository.

---

## Tools Used
- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Project Structure
brain-drain-ngram-project/
├── data/
│ └── ngram_wide.csv
├── notebooks/
│ └── brain_drain_ngram_analysis.ipynb
├── figures/
│ └── *.png
├── report/
│ └── brain_drain_google_ngram_blog.pdf
└── README.md

---

## Key Takeaways
- The term *brain drain* shows minimal usage before the 1950s and rises sharply after the 1960s.
- Brain drain discourse is closely linked with globalization and human capital.
- The analysis reflects changes in academic and policy attention, not actual migration flows.

---

## Next Experiments
If more time were available, future analysis could:
- Compare brain drain with concepts such as *brain gain* or *brain circulation*
- Normalize trends further to compare niche and broad concepts
- Extend the analysis to additional migration-related terms
- Combine Ngram trends with real-world migration or education datasets