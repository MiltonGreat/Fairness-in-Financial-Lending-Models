# Fairness in Financial Lending Models

This project addresses the critical need for fairness and transparency in financial lending decisions. Using Home Mortgage Disclosure Act (HMDA) data, we developed a comprehensive framework to:

- Detect algorithmic bias across protected demographic groups
- Measure compliance with regulatory standards (4/5ths rule, demographic parity)
- Mitigate bias using state-of-the-art techniques
- Provide actionable insights for fair lending practices

## Key Features

**Multi-Tier Fairness Analysis**
- Tier 1: Regulatory compliance & statistical testing
- Tier 2: Advanced model interrogation & causal reasoning
- Tier 3: Business & strategic opportunity analysis
- Tier 4: Systemic pattern identification

**Bias Detection & Mitigation**
- Demographic Parity Difference
- Equalized Odds Difference
- 4/5ths Rule Compliance Testing
- Threshold Optimization
- Reweighting Techniques
- Group-specific Threshold Adjustment

## Model Framework

- Algorithms: Logistic Regression & Random Forest
- Interpretability: SHAP analysis & feature importance
- Validation: Comprehensive fairness metrics
- Visualization: Interactive dashboards and reports

## Key Findings

**Critical Fairness Issues Identified**
- Ethnicity-Based Disparities
- Ethnic Group	Approval Rate	4/5ths Rule Status
- Hispanic/Latino	62.7%	✅ Compliant
- Not Hispanic/Latino	46.1%	🚩 Violation
- Information not provided	54.9%	✅ Compliant
- Demographic Parity Difference: 0.622 (Substantial disparity)

**Gender-Based Disparities**
- All major gender groups show similar approval rates (48-53%)
- "Not applicable" group shows 0% approval rate
- Demographic Parity Difference: 0.532

**Top Underserved Markets**
- Not Hispanic/Latino, Low-income neighborhoods (Highest opportunity)
- Not Hispanic/Latino, High-income neighborhoods
- Information not provided, Lower-middle income

**Channel Performance Variations**
- Highest Approval: Purchaser Type 2 (75.7%)
- Most Balanced: Purchaser Type 6 (62.6% approval, higher-income applicants)
- Lowest Approval: Purchaser Type 0 & 5 (~30%)

## Results & Impact

**Fairness Metrics Improvement**
- Before Mitigation: 0.626 demographic parity difference
- After Mitigation: 0.006 demographic parity difference
- Improvement: 99% reduction in fairness disparity

**Model Performance**
- Accuracy Maintained: 74.8% (after mitigation)
- Fairness Achieved: Near-perfect demographic parity
- Business Impact: Enabled compliant model deployment

### Source

[HMDA Dataset for Mortgage Loans in 2022](https://www.kaggle.com/datasets/mdtarekislam/hmda-dataset-for-mortgage-loans-in-2022)
