# OSLSVF: Online Semi-Supervised Learning and Selection in Variable Feature Spaces

![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Abstract
The online learning paradigm based on the Doubly-stream data feature space is attracting considerable attention due to its perceived flexibility. However, its practical application is limited by three key factors. First, previous research has mainly focused on homogeneous data feature types, which do not reflect the heterogeneity that is often present in real-world data. Second, while prior work has emphasized the importance of complete data labeling, the cost of achieving this is prohibitively high when dealing with long time streaming data. Third, the inclusion of incremental data features can slow down model convergence and reduce prediction accuracy, even when the key features are present. To address these challenges, this study proposes a new problem called Online Semi-Supervised Learning and Selection in Variable Feature Spaces (OSLSVF). This paper address this problem by establishing the relationship between the observation space and the latent space through a conjugate model, which enables the measurement of distance. An adaptive geometric spatial distance metric is used to establish the relationship between unlabeled and true labels. Finally, L1 regularity is used to establish the feature space distribution to filter important features. Rich experimental results are documented to demonstrate the feasibility and effectiveness of our proposed method.

## File

The overall framework of this project is designed as follows
1. The **dataset** file is used to hold the datasets and lables

2. The **source** file is all the code for the model

3. The **Result** is for saving relevant results (e.g. CER, Figure)

### Getting Started
1. Clone this repository

```
git clone https://github.com/OSLMF/OSLMF_Algo.git
```

2. Make sure you meet package requirements by running:

```python
pip install -r requirements.txt
```

3. Running OSLSVF model

```python
python OSLSVF_Cap.py
```

or 

```python
python OSLSVF_Tra.py
```
