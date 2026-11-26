Telecom Customer Churn Analysis

## Final Assignment Work

This project analyzes telecom customer churn and proposes a targeted
retention strategy for Saudi Arabia.

### What I did

- Combined the Client and Record datasets using `Customer_ID`.
- Explored churn patterns using exploratory data analysis.
- Investigated equipment age, usage, and customer tenure.
- Built an XGBoost classification model.
- Evaluated accuracy, precision, recall, and F1-score.
- Ranked customers by predicted churn risk.
- Proposed a targeted retention pilot for high-risk customers with older equipment.

### Main results

- Accuracy: 63%
- Churn recall: 64%
- F1-score: 63%
- `eqpdays` was the most important model feature.
- The top 10% highest-risk customers included 1,567 actual churners.
- The observed churn rate in this targeted group was 78.35%.

### Proposed strategy

Test equipment-upgrade, trade-in, or plan-upgrade offers for high-risk customers
with older equipment.

### Limitations

The dataset contains a general churn label and does not explain why customers
churned. The results show association, not proof that older equipment causes
churn. Financial impact was not estimated because actual company costs and
customer-value data were unavailable.

### Files

- The PDF contains the explanatory presentation.
- The notebook contains the analysis and model work.

### External references

- Opensignal
- Argaam

### License

Apache License 2.0
