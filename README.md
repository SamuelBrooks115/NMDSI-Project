# NMDSI-Project
Research Project LSTM: Money Laundering Detection
This repository contains the code, dataset preprocessing steps, and the LSTM-based model developed for detecting money laundering transactions. This project was part of my summer research focused on building a machine learning model using Long Short-Term Memory (LSTM) networks to classify suspicious transactions within a financial dataset.

Overview
The primary objective of this research was to detect fraudulent money laundering transactions using the IBM AML transaction dataset. Given the nature of the dataset and the problem at hand, LSTM networks were chosen for their ability to capture patterns in sequential data, which is critical for understanding the flow of financial transactions over time.

Project Structure
Data Preprocessing: File that takes in the Hi_Small_Trans file from the IBM Kaggle page and completes all preprocessing steps.
Model + Eval: File includes model architecture, evaluation metrics, and results. 

Future Work

This project has primarily focused on using an LSTM model to classify transactions, but there are several potential directions for future work:

1. Graph Convolutional Networks (GCNs): Incorporating relational data between entities (e.g., account holders or banks) to detect patterns in the financial network.
2. Hyperparameter Tuning and Regularization: Enhancing model robustness by fine-tuning parameters and applying advanced regularization techniques.
3. Real-Time Detection: Implementing streaming data capabilities to make the model practical for real-time fraud detection in the financial industry.

I aim to tweak the model parameters to achieve better detection results, as the current state of the project reflects the progress made during the summer. There is room for further optimization and exploration.

In addition to improving the LSTM model, other approaches worth exploring include:

- GCNs: To model relationships between entities and improve fraud detection through network analysis.
- Transformer Models: For capturing long-range dependencies in transaction data, potentially improving accuracy.
- RNNs with Attention: To focus on key transaction patterns that may indicate suspicious activity.
- Hybrid LSTM + CNN Models: To combine sequential and convolutional layers for better feature extraction and classification.


Citations
- Link to Kaggle Dataset: https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml?select=HI-Small_Trans.csv
- Link to Paper on GCN + LSTM Approach: https://eprints.bournemouth.ac.uk/38005/10/s11063-022-10904-8.pdf
- Link to Paper reviewing different AML approaches: https://ieeexplore.ieee.org/document/9803072
