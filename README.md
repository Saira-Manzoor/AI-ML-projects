# AI/ML Projects
## Objective
This repository serves as a comprehensive portfolio showcasing diverse AI/ML projects. The primary objective is to gain hands-on experience and demonstrate proficiency in key machine learning domains, including anomaly detection, multi-label classification, satellite image analysis, and credit risk assessment. Each project tackles a real-world problem, from financial market surveillance to environmental monitoring and financial risk management.

## Project Details
Task 1: Financial Time-Series Anomaly Detection
Objective: Build a tool to identify anomalies in stock price trends to detect unusual activities or potential market manipulations.

**_Dataset: Yahoo Finance Stock Market Dataset**
**
Steps:**

- Download and preprocess historical stock price data for a few chosen companies.

- Calculate financial indicators (e.g., Simple Moving Average (SMA), Exponential Moving Average (EMA), Relative Strength Index (RSI), Bollinger Bands).

- Apply unsupervised anomaly detection techniques such as Isolation Forest or DBSCAN.

- Develop a time-series forecasting model (e.g., LSTM or Prophet) to identify deviations from predicted trends.

- Visualize detected anomalies on stock price trends for clear interpretation.

**Outcome:** A robust tool or detailed report identifying anomalies in stock price trends and highlighting possible market manipulations.

**Task 2: Multi-Label Emotion Recognition from Text**
**Objective:** Develop a system capable of classifying multiple emotions (e.g., joy, sadness, anger) present in textual data.

Dataset: GoEmotions Dataset by Google

**Steps:**

- Preprocess the dataset, specifically addressing imbalanced data distribution among emotion labels.

- Fine-tune a transformer model, such as BERT, for multi-label text classification.

- Evaluate the model's performance using appropriate metrics like Hamming loss and F1 score (micro, macro, weighted).

- Test the developed system on real-world textual data, such as customer feedback or social media posts, to demonstrate its practical application.

- Outcome: A system capable of analyzing emotional tones in text and assigning multiple relevant emotion labels.

**Task 3: Satellite Image Analysis for Deforestation Monitoring**
**Objective: **Utilize satellite imagery to detect and monitor deforestation areas over time.

Dataset: Planet: Understanding the Amazon from Space

**Steps:**

- Preprocess multi-band satellite images, preparing them for land cover analysis.

- Train Convolutional Neural Networks (CNNs) for accurate land classification (e.g., forest, non-forest, water, agriculture).

- Perform change detection analysis using sequential images to precisely identify areas affected by deforestation.

- Visualize environmental changes over time, highlighting deforestation trends and affected regions.

- Outcome: A system that effectively detects and monitors deforestation, providing valuable insights for environmental conservation.

**Task 4: Credit Risk Analysis**
**Objective:** Build a predictive model to assess the creditworthiness of customers and flag high-risk customers for financial institutions.

**Dataset**: Give Me Some Credit Dataset
**
**Steps:****

- Preprocess the dataset, handling missing data and addressing class imbalances using techniques like SMOTE (Synthetic Minority Over-sampling Technique).

- Engineer relevant features related to customer income, debt, and repayment history to improve model performance.

- Train various machine learning models, including Random Forest, Gradient Boosting, or XGBoost, to identify the most effective approach.

- Evaluate the model rigorously using appropriate metrics such as AUC-ROC, Precision, Recall, and F1-score to ensure its reliability.

**Outcome:** A robust system that reduces default rates by accurately flagging high-risk customers, thereby supporting better financial decision-making.

Submission Requirements
For each task, the following deliverables are expected:

Python Code:

Well-documented and commented scripts for all implemented models and preprocessing steps.

Code should be clean, readable, and follow best practices.

**Report:
**
- Detailed explanation of dataset preprocessing steps, including handling of missing data and imbalances.

- Rationale behind model selection, including comparisons of different approaches if applicable.

- Discussion of challenges faced during the project and the solutions implemented to overcome them.

- Evaluation results and interpretation of metrics.
