# Quantitative Text Analysis for Community Violence Intervention (CVI)

This repository contains code used for a Quantitative Text Analysis (QTA) of interview transcripts collected from a Community Violence Intervention (CVI) programme: *Project Restore Bed-Stuy* (PRB), based in Brooklyn, New York.

## Overview

The analysis explores how participants’ narratives shift over time, with a particular focus on:

- Emotional tone  
- Identity and self-perception  
- Future orientation  
- Social connection  
- Perceived programme impact  

Language is examined as both a **signal** and **mechanism** of personal transformation within a trauma-informed, community-based intervention setting.

## Repository Contents

- `Processing_And_KWIC_Code.R`  
  Main R script for cleaning transcripts, tokenising data, and extracting Key Words in Context (KWIC). Includes keyword categorisation, frequency counts, and normalisation per 1,000 words.

- `Processing_And_KWIC.html`  
  A knitted output providing a visual summary of the KWIC pipeline and processing stages.

- `Sentiment_Analysis.ipynb`  
  Jupyter Notebook for sentiment analysis using the VADER model, adapted for informal and culturally specific language. Sentiment scores were compared across midline and endline interviews.

## Methodology

- Thematic keywords were selected based on relevance to PRB’s Theory of Change, supported by frequency analysis and existing literature on desistance, identity, and restorative justice.
- Preprocessing and KWIC were conducted in R using the `quanteda`, `tidytext`, and `dplyr` packages.
- Sentiment analysis was carried out in Python using the VADER sentiment lexicon (`nltk.sentiment.vader`).
- KWIC quotes were lightly edited for clarity and coherence, preserving narrative intent while ensuring interpretability.

## Data
Interview transcript data used in the analysis are not included in this repository, due to ethical considerations and participant confidentiality.

While representative quotes from the KWIC analysis are presented in the paper, the full KWIC outputs are also not shared publicly for the same reasons. However, documentation of the analysis process is available through the provided code, and evidence can be made available on request for academic or evaluation purposes.
