# sklearn Imports Reference

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.linear_model import LinearRegression
from sklearn.cluster import KMeans
from sklearn.ensemble import RandomForestClassifier
```

| Import | What it's for |
|--------|--------------|
| `pandas` + `seaborn` + `matplotlib` | Data handling, correlation heatmap, all plots |
| `train_test_split` | Split data for training & testing (regression + classification) |
| `LabelEncoder` | Encode categorical `food_type`, `transport_mode`, etc. into numbers |
| `LinearRegression` | Q2 — Predict carbon footprint from behavioural inputs |
| `KMeans` | Q3 — Cluster individuals into carbon behaviour profiles |
| `RandomForestClassifier` | Q4 — Classify carbon impact level (Low/Medium/High) |
