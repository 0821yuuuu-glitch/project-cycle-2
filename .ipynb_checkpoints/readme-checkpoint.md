# Project Cycle 2: Confidence Intervals and One-Sample Inference

### 1. Group Information
* **Group Number**: Group 03
* **Team Members**: 余曜廷、蘇孟孜
* **Dataset**: YRBS_2007.csv

### 2. Selected Variables and Benchmarks
* **Behavioral Variable**: `CurrentAlcoholUse`
    * **Benchmark ($p_0$)**: 0.35
* **Continuous Variable**: `HowMuchDoYouWeighWithoutShoesInKG`
    * **Benchmark ($\mu_0$)**: 68.0

### 3. Research Questions
* **Proportion Analysis**: Is the proportion of students who currently use alcohol significantly different from 0.35?
* **Mean Analysis**: Is the mean weight of students significantly different from 68.0 kg?

### 4. Final Conclusion

* **Proportion Test Result (Alcohol)**: **Reject H0**
    * **Interpretation**: The sample proportion of alcohol use is **0.455**, which is significantly different (and higher) than the benchmark of **0.35** (p-value < 0.05). The 95% confidence interval is **[0.446, 0.464]**.
    
* **Mean Test Result (Weight)**: **Reject H0**
    * **Interpretation**: The sample mean weight is **68.43 kg**. Since the p-value (**0.006**) is less than 0.05 and the 95% confidence interval **[68.12, 68.73]** does not include the benchmark of **68.0**, we conclude that the mean weight is significantly different from the benchmark.
