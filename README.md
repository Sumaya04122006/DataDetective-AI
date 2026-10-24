# 🔎 DataDetective AI

**An interactive data investigation and quality analysis tool built with Python and Gradio.**

🚀 **Live Demo:** https://c30b0b978c79b4ebd4.gradio.live/

> **Note:** The live demo uses a temporary Gradio sharing link. It may become unavailable when the Google Colab runtime disconnects.

## Problem Statement

Raw datasets frequently contain missing values, duplicate records, and unusual observations. Manually inspecting these issues can be time-consuming and challenging, especially for beginners learning data science.

## Solution

DataDetective AI provides a single interface to upload CSV files, inspect data quality, explore numerical distributions, flag potential anomalies, and export cleaned datasets.

## Key Features

- CSV dataset upload
- Missing-value and duplicate detection
- Column-level data-quality profiling
- Isolation Forest anomaly detection
- Descriptive statistics
- Interactive Plotly visualizations
- Optional missing-value imputation and duplicate removal
- Downloadable cleaned datasets and anomaly records
- No external AI API key required

## Technology Stack

Python, Gradio, Pandas, NumPy, Scikit-learn, Plotly, and Google Colab.

## Getting Started

1. Open the live demo above or run the notebook in Google Colab.
2. Upload a CSV dataset or use the included sample dataset.
3. Investigate data quality, statistics, visualizations, and potential anomalies.
4. Apply optional cleaning operations and download the results.

## Limitations

This is a prototype for exploratory data analysis. Anomaly flags are not confirmed errors, and cleaning decisions should be validated before use. The current implementation does not use a generative AI model.

## Project Status

Prototype — active development.

