# Sleep Deprivation, Cognitive Performance, and Emotional Regulation

## Overview
This project explores the relationship between sleep duration, sleep quality, and daytime sleepiness with cognitive performance and emotional regulation. It uses behavioral data from standardized cognitive neuroscience tasks including the Stroop task, N-Back task, and Psychomotor Vigilance Task (PVT), with a focus on interpretable, research-oriented methods.

---

## Dataset
The dataset was obtained from Kaggle and is not redistributed in this repository due to licensing restrictions.

**Source:**  
https://www.kaggle.com/datasets/sacramentotechnology/sleep-deprivation-and-cognitive-performance

It includes data from 60 participants collected in 2024, with measures of:
- Sleep duration and quality
- Daytime sleepiness
- Cognitive task performance (Stroop, N-Back, PVT)
- Emotional regulation
- Demographics and lifestyle factors (age, gender, BMI, caffeine intake, physical activity, stress)

For instructions on accessing the data, see `data/README.md`.

---

## Analysis Workflow
This project follows a standard research workflow:
1. Data overview and documentation
2. Data loading and initial inspection
3. Data cleaning and preprocessing planning
4. Exploratory analysis of sleep–cognition relationships
5. Results summary and interpretation

---

## Key Findings
- Sleep duration and sleep quality were not significantly associated with executive control (Stroop task).
- Vigilance (PVT) showed a weak, non-significant trend with sleep duration.
- Working memory (N-Back accuracy) showed no significant associations with sleep measures.
- Overall, individual differences in sleep measures did not strongly predict cognitive performance across domains in this healthy sample.

---

## Figures

![Sleep duration vs Stroop reaction time](figures/SleepHours_vs_Stroop.png)
![Sleep duration vs PVT reaction time](figures/SleepDur_vs_PVT.png)

*(See `figures/` directory for full visualizations.)*

---


## Repository Structure

```
sleep-deprivation-cognition-emotion/
├── README.md
├── data/
│   └── README.md
├── notebooks/
│   ├── 01_data_overview.md
│   ├── 02_data_loading_and_inspection.md
│   ├── 03_data_cleaning.md
│   ├── 04_exploratory_analysis.ipynb
│   └── 04_results_summary.md
└── figures/
    ├── .gitkeep
    ├── daytime_sleepiness_vs_pvt.png
    ├── sleep_hours_vs_nback.png
    ├── sleep_hours_vs_pvt.png
    ├── sleep_hours_vs_stroop.png
    └── sleep_quality_vs_stroop.png
```

---

## Methods and Tools
- Python  
- pandas  
- matplotlib  
- scipy  

These were selected for their interpretability and suitability for exploratory behavioral analysis.

---

## Relevance
This repository demonstrates skills in cognitive neuroscience task analysis, behavioral data exploration, reproducible coding practices, and transparent reporting.
