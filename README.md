# Job Title Classification

This project focuses on classifying job titles using a given dataset. A BERT model was employed, which was fine-tuned with a classification head to achieve optimal results.

## Overview
In the age of data-driven decision-making, accurately classifying job titles can provide valuable insights into job market trends and employee skills. This project utilizes a pre-trained BERT model for this classification task, leveraging its ability to understand contextual relationships in text.

## Performance Metrics
After preparing the data and fine-tuning the BERT model, the following performance metrics were obtained:

Accuracy: 0.8512 <br />
Precision: 0.9570 <br />
Recall: 0.9215 <br />
F1-score: 0.9390 <br />

These results indicate a high level of performance, particularly in terms of precision and recall, making the model suitable for real-world applications.

## Installation

Prepare enviroment
```javascript
conda create -n Classify_Job_Titles python=3.10.12
conda activate Classify_Job_Titles

```
Install the required dependencies:
```javascript
pip install -r requirements.txt
```
