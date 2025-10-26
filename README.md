Step 9: Insights & Interpretation

### Key Findings
- Average sleep duration: 6–8 hours.
- Quality of sleep improves with higher daily steps and lower stress.
- Stress Level correlates positively with Heart Rate.

### Trends & Anomalies
- Outliers: few people sleeping <4 hours.
- Occupation influences lifestyle metrics.
- Some high-activity but poor-sleep cases — potential lifestyle imbalance.

### Relationships Between Features
| Relationship | Type | Observation |
|---------------|------|-------------|
| Sleep Duration ↔ Quality Of Sleep | Positive | More sleep = better quality |
| Stress Level ↔ Heart Rate | Positive | Stress raises HR |
| Daily Steps ↔ Stress Level | Negative | More steps = less stress |

### Implications for Modeling
- Strong predictors: Sleep Duration, Daily Steps, Heart Rate, Activity Level.
- Encode categorical features (Gender, Occupation, BMI Category).
- Possible targets: Quality Of Sleep (regression), Stress Level (classification).
