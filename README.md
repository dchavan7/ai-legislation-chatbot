# Predicting AI Legislation Outcomes in the U.S. Congress: Natural Language Processing and Machine Learning Approach

## Project Overview
This project analyzes 1,033 AI-relevant bills introduced across the 115th through 118th Congress (2017–2024) to identify what 
predicts legislative advancement using NLP and machine learning.

## Research Questions
1. How many AI legislative bills have been introduced and passed between the 115th and 118th Congress?
2. What features make AI legislation more or less likely to pass?

## Data Source
- Congress.gov API (https://api.congress.gov)
- Congressional sessions: 115th–118th (2017–2024)
- Total bills collected: 67,312
- Final AI-relevant dataset: 1,033 bills

## How To Run
1. Install dependencies: pip install -r requirements.txt
2. Run summary collection: python get_summaries.py
3. Run NLP pipeline: python NLP.py
4. Run models: python model.py

## Reproducibility
All random seeds set to 42.
See requirements.txt for full package versions.

## AI Use Disclosure
Claude by Anthropic was used to assist with code development. All content was reviewed by the author.
