# Analyze A/B Test Results

This project evaluates whether a new webpage design increases conversion rates for an e-commerce platform through A/B testing and statistical analysis.

## 📊 Project Overview

An e-commerce company conducted an A/B test to compare the performance of a new webpage (treatment group) with the existing one (control group). Each user in the dataset was randomly assigned to either group, and we analyzed their conversion behavior.

### Dataset Features

- `country`: Country of origin (US, UK, CA)
- `group`: Control or Treatment
- `converted`: Binary outcome (1 = converted, 0 = not converted)

---

## 🧠 Key Objectives

- Understand overall and segmented conversion rates
- Test statistical significance of observed differences
- Use both **simulation-based testing** and **logistic regression modeling**

---

## 📈 Results Summary

- **Control Conversion Rate:** 10.53%
- **Treatment Conversion Rate:** 15.53%
- **Observed Difference:** +5.00%
- **p-value:** 0.000 — statistically significant

### By Country
| Country | Control | Treatment |
|---------|---------|-----------|
| US      | 10.7%   | 15.8%     |
| UK      | 10%     | 14%       |
| CA      | 9%      | 15%       |

The new page outperformed the old one in all regions.
----
# Acknowledgments 🙌
This project was conducted as part of the **DECI and Udacity Data & AI Track** - Final Project. 

![image](https://github.com/user-attachments/assets/404c7ad8-a894-4542-b23f-c0128d113bfd)
![image](https://github.com/user-attachments/assets/bd2c9a02-05f2-4344-8448-58249cc42f90)
![image](https://github.com/user-attachments/assets/5009f723-1a9f-44b4-b316-e2b4894850b0)


---

## 🔍 Conclusion

The analysis indicates that the new webpage significantly improves conversion rates across all tested regions. Statistical and regression results support rolling out the new design.

---

## 📁 Files

- `analyze_ab_test_results_notebook_new.ipynb`: Full notebook with all analysis and code
- `analyze-a_b-test-results.pdf`: Presentation-style summary
