# DS512/513
-test

# DS514/515

## Hotel Cancellation Model Summary

### XGBoost Model Performance

- **Accuracy:** Achieved the highest accuracy among tested models at **0.85**
- **Recall (Cancellation Class 1):** Demonstrated a recall of **0.67** (highest among all models)
- **Optimized Hyperparameters:**
  - `learning_rate`: 0.1
  - `max_depth`: 13
  - `n_estimators`: 600
- **Performance on Unseen Data:** Results are promising, indicating good generalizability

### Insights & Next Steps

- **Data Imbalance:** Only ~20% (actual percentage to be specified) of bookings are cancelled—imbalanced data
   - **Action:** Gather more data for cancelled bookings to improve model robustness
- **Probability Model:** Develop a cancellation probability model to further aid business decisions

### Visual Results

```
![Performance Chart](path/to/your/image1.png)
![Confusion Matrix](path/to/your/image2.png)
```

---
