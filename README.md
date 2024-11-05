# Predoc Job Description Analysis

This project analyzes requirements and qualifications for Pre-doctoral (Predoc) Research Assistant positions using Python-based text analysis and visualization techniques.

## Project Overview

The notebook provides an end-to-end workflow for processing, analyzing, and visualizing job description data to identify key skills and qualifications frequently sought in Predoc roles. Key features include data parsing, keyword frequency analysis, and word cloud visualization.

## Features

- **Text Parsing**: Processes text from multiple job descriptions and compiles a list of required skills and qualifications.
- **Frequency Analysis**: Extracts and quantifies the frequency of common keywords.
- **Word Cloud Visualization**: Creates a word cloud to visually represent the most common requirements.

## Installation

Ensure you have Python installed. Then, install the required libraries:

```bash
pip install nltk wordcloud matplotlib PyPDF2
```

## Usage
1. **Load Requirements Data**: Insert the list of job requirements as strings.
2. **Generate Word Cloud**: Run the notebook cells to produce a visual representation of key qualifications.
3. **Optional Save**: Modify the output path to save the word cloud as a PDF or other image formats.

