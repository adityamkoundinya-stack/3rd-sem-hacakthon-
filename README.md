# 3rd-sem-hacakthon-

Your **Automotive Model 1 has strong accuracy and precision, but its recall needs attention.** Let's compare it with Model 2 using the final recorded metrics.

## **1. Automotive ML performance comparison**

Model 1: Machine Failure Prediction · Model 2: Production Bottleneck Prediction

| Performance metric | Model 1                          | Model 2     |
| ------------------ | -------------------------------- | ----------- |
| Algorithm          | Random Forest / selected model\* | Extra Trees |
| Accuracy           | **98.05%**                       | 26.52%      |
| Precision          | **91.43%**                       | 23.65%      |
| Recall             | 47.06%                           | 34.84%      |
| F1-score           | **62.14%**                       | 24.40%      |
| Balanced accuracy  | 73.00%                           | 34.84%      |

*The Model 1 algorithm name should be confirmed if you want it included in your final documentation.*

## **2. Model 1 – What the results mean**

# **98.05%**

**Accuracy**

Excellent overall correctness

# **91.43%**

**Precision**

Predicted failures are usually genuine

# **47.06%**

**Recall**

Less than half of actual failures detected

# **62.14%**

**F1-score**

Precision and recall balance

### **Confusion matrix interpretation**

| Actual / Predicted | Normal | Failure |
| ------------------ | ------ | ------- |
| Normal             | 1,929  | 3       |
| Failure            | 36     | 32      |

Out of 68 actual machine failures:

- 32 were correctly identified.
- 36 failures were missed.
- Only 3 normal cases were incorrectly flagged as failures.

**Main concern:** The model is reliable when it predicts a failure, but it misses 52.94% of actual failures. For predictive maintenance, this is a significant limitation.

## **3. Overall automotive industry assessment**



Model 1: Strong baseline

Model 2: Weak baseline



- **Model 1:** Promising for identifying likely machine failures, but its low recall limits its usefulness as an early-warning system.
- **Model 2:** Its performance is weak, with accuracy only slightly above the 25.45% majority-class baseline.

## **4. Report-ready conclusion**

The Automotive Industry module incorporates two machine learning models: Machine Failure Prediction and Production Bottleneck Prediction. The Machine Failure Prediction model achieved 98.05% accuracy and 91.43% precision, demonstrating strong overall classification performance. However, its recall of 47.06% indicates that a substantial proportion of actual failures remain undetected. The Production Bottleneck Prediction model achieved 26.52% accuracy and 23.65% macro precision, indicating limited predictive performance. Together, these models establish an initial foundation for manufacturing predictive intelligence, with different levels of reliability across the two applications.

**My recommendation:** Keep both models' current results documented as they are. We can report Model 1 as a promising baseline and Model 2 as an experimental baseline without overstating their capabilities.














