# A Bayesian Network–Based Model for Network Intrusion Prediction
This repository contains the implementation, analysis, and experimental results of a Bayesian Network–based Intrusion Prediction Model developed using the NSL-KDD dataset. The project follows a structured machine-learning workflow encompassing data preprocessing, feature engineering, structure learning using the Max–Min Hill Climbing (MMHC) algorithm, and influence/scenario analyses for evaluation. 
This work is based on the paper:
> A network intrusion prediction model using Bayesian network, Ijegwa David Acheme, Adebanjo Adeshina Wasiu, & Glory Nosa Edegbe (2024), World Journal of Advanced Research and Reviews, 23(01), 2813–2821.
## Overview
Intrusion Detection Systems (IDS) play a critical role in modern cybersecurity by detecting and preventing unauthorized access and malicious activities in computer networks. This project implements a Bayesian Network-based IDS using key extracted features from the NSL-KDD dataset, demonstrating effective performance in predicting network intrusions.
## Features
### Key Capabilities
- Preprocessing pipeline for symbolic-to-numeric conversion and label binarization.
- Feature selection using statistical methods.
- Structure learning using the Max–Min Hill Climbing (MMHC) hybrid algorithm.

### Technologies Used
- Python (NumPy, Pandas, Scikit-learn)
- Jupyter Notebook

### Dataset
The NSL-KDD dataset is a refined and improved version of the KDD’99 dataset. It resolves issues such as redundant records and class imbalance, making it a widely adopted benchmark for IDS research.
- 41 features per network connection
- 22 attack categories in the training set
- 17 additional unseen attacks in the testing set

Contains 4 major attack families:
- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)

Dataset reference:
NSL-KDD Data set for Network-based Intrusion Detection Systems. Available at: [https://www.kaggle.com/datasets/hassan06/nslkdd](https://www.kaggle.com/datasets/hassan06/nslkdd)

## Repository
```
|-- NSL_KDD_Train.csv
|-- NSL_KDD_Test.csv
|-- intrusion_prediction_model.ipynb
|-- README.md
```

## How to Run
Open the main notebook:
```
jupyter notebook notebooks/intrusion_prediction_model.ipynb
```

## References
1. Acheme, I. D., Wasiu, A. A., & Edegbe, G. N. (2024). A network intrusion prediction model using Bayesian network. World Journal of Advanced Research and Reviews, 23(1), 2813–2821.
2. Moustafa, Nour, and Jill Slay. "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)."Military Communications and Information Systems Conference (MilCIS), 2015. IEEE, 2015.​
3. Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of theUNSW-NB15 data set and the comparison with the KDD99 data set." Information Security Journal: A Global Perspective (2016): 1-14.​
4. Russell, S. J., & Norvig, P. (2020). Probabilistic reasoning. In Artificial intelligence: A modern approach (4th ed., pp. [412-460]). Pearson.
