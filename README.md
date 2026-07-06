# Reducing User Churn & Increasing Premium Adoption: A Spotify Product Analytics Case Study

A product management case study that turns a behavioral dataset into a scoped growth initiative, pairing a data analysis notebook with a full Product Requirements Document (PRD) for a Premium conversion & retention program.

## Overview

Spotify (simulated data) monetizes through Premium subscriptions and ad-supported free listening. This project analyzes 50,000 simulated user behavior records to answer the questions a Growth PM needs answered before writing a roadmap:

1. **Who converts to Premium, and who doesn't?**
2. **Which free users are the best upsell targets?**
3. **Which users are at risk of disengaging, and what predicts it?**

The analysis findings are then translated into a formal PRD proposing a phased product initiative to act on them.

**Dataset:** [Spotify User Behavior and Pattern](https://www.kaggle.com/datasets/sahilislam007/spotify-user-behavior-and-pattern) (Kaggle, 50,000 simulated users)

## Contents

| File | Description |
|---|---|
| `spotify_premium_case_study.ipynb` | The analysis notebook, framed as a PM case study: business problem, objectives, hypotheses, EDA, funnel analysis, segmentation, churn modeling, and product recommendations. |
| `spotify_premium_retention_prd.docx` | A complete Product Requirements Document for the initiative the analysis supports. |

## Tech

- Python 3
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `kagglehub` (to download the dataset)

## How to Use This Project

1. Run the notebook end-to-end to reproduce the analysis and metrics in Section 10 ("Product Summary Dashboard").
2. Before each planning cycle, refresh the PRD's Goals & Success Metrics table (Section 4) with the notebook's latest output. The two documents are meant to stay in sync.
3. Use the PRD as-is for stakeholder review, or adapt the epics/timeline to the actual capacity and tooling.

PRD: https://docs.google.com/document/d/1w7mwXFbPfp7aqQl_9zw9L0Ivk8cYx0R7hBJr5AV6LwI/edit?usp=sharing
