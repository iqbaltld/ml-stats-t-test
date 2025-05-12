## Paired T-Test & Other T-Tests Analysis

This project demonstrates hypothesis testing using various **t-tests** to analyze whether a new drug significantly reduces blood pressure. It uses measurement data before and after treatment and evaluates the statistical significance of the observed changes.

---

## 🧪 Hypotheses

- **Null Hypothesis (H₀):** The drug has **no effect** on blood pressure.
- **Alternative Hypothesis (H₁):** The drug **does affect** blood pressure.

---

## 🔬 T-Tests Covered

| Test Type            | When to Use                                             |
|----------------------|----------------------------------------------------------|
| **Paired t-test**     | When comparing means from the same subjects pre/post   |
| **One Sample t-test** | When comparing the sample mean to a known/target value |
| **Two Sample t-test** | When comparing means from two independent groups       |


Each test is implemented in the notebook with comments and outputs explaining the steps and conclusions.

---

## 📈 Visualization

A **boxplot** is included in the notebook to visually compare blood pressure values before and after treatment.

```python
plt.boxplot([before_treatment, after_treatment], labels=['Before', 'After'])
```



## 📣 Author

**Muhammed Iqbal** – [LinkedIn](https://linkedin.com/in/iqbaltld)
