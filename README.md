# Lenskart Brand Perception & Customer Segmentation Analysis

Marketing analytics project analyzing Lenskart's brand perception, customer segments, and competitive positioning in the Indian eyewear market, based on a 77-respondent consumer survey.

## Project Overview

This project explores how consumers perceive Lenskart relative to competitors (Ray-Ban, Titan Eyeplus, GKB Optics, Local Brands) and identifies distinct customer segments to guide targeted marketing and pricing strategy.

## What This Analysis Does

- **Survey Data Processing**: Cleans and analyzes responses from a Lenskart Brand Perception Survey covering demographics, product usage, brand awareness, and purchase drivers.
- **Customer Segmentation (K-Means Clustering)**: Uses the elbow method to determine optimal cluster count, then segments customers into two groups:
  - **Segment 1 (61%)**: Quality and experience driven, values fashion and premium buying experience.
  - **Segment 2 (39%)**: Price-sensitive, prioritizes affordability and durability over branding.
- **Perceptual Mapping**: Plots Lenskart against competitors on Quality vs Price-to-Value axes to visualize competitive positioning.
- **Conjoint / Regression Analysis**: Runs an OLS regression to quantify how quality and price-to-value ratio drive likelihood to recommend Lenskart (R-squared = 0.565, both predictors significant at p < 0.001).

## Key Findings

- Lenskart is perceived as high quality with strong price-to-value, outperforming Titan Eyeplus, GKB Optics, and Local Brands on both dimensions.
- 98.7% brand awareness among respondents; 57.1% hold a Lenskart Gold Membership.
- 58.4% of customers would switch brands if prices increased, indicating high price sensitivity despite strong brand perception.
- Quality (coef 0.55) is a stronger driver of recommendation likelihood than price-to-value (coef 0.35).

## Repo Contents

| File | Description |
|---|---|
| `Lenskart_Analysis_TEAM_5.ipynb` | Full analysis notebook: data loading, EDA, clustering, perceptual mapping, regression |

## Tools & Libraries

Python, Pandas, Scikit-learn (KMeans, PCA), Matplotlib, Statsmodels (OLS regression)

## Data Source

Primary survey data collected via Google Forms (Lenskart Brand Perception Survey), 77 respondents.

## Team

Team 5, MSBA 2025