# Data Loading and Initial Inspection

This document describes how the sleep deprivation dataset is loaded and checked before analysis.

## Data Source

The dataset was downloaded from Kaggle and is not included in this repository due to licensing restrictions.

## Loading the Dataset

```python
import pandas as pd

df = pd.read_csv("data/raw/sleep_cognition_emotion_raw.csv")

```

## Initial Inspection

```python
df.head()
df.info()
df.describe()
```

