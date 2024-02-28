# LoS-HM-DA
**Length of Stay prediction for Hospital Management using Domain Adaptation**

Email: naomiewamba@ymail.com

***Note: This source code repository is a work in progress.***
_______________________________________________________________________________

**Abstract**

Anticipating inpatient length of stay (LoS) can be of crucial aid for efficient hospital management, admissions planning, resource allocation and care quality improvement. Anticipating LoS can be achieved by applying machine learning techniques on historical patient data for developing predictive models. Ethically, these models cannot serve as substitutes for medical unit heads, solely responsible for authorizing patients’ discharge, but they can be exploited by management systems for effective hospital planning.  Therefore, the prediction system should be designed and adapted to work in a true hospital setting.
This study focuses on early hospital LoS prediction for different admission units and employs domain adaptation to leverage information learned from a potential source domain. Time series data from 110,079 admissions into 8 intensive care units (ICUs) and 60,492 admissions into 9 ICUs were respectively extracted from eICU-CRD and MIMIC-IV and fed into a Long-Short Term Memory network and a Fully connected network to train a source domain model. Learned weights were then transferred either partially or fully from a source domain to target domains. SHapley Additive exPlanations (SHAP) algorithms were used to study the effect of weight transfer on feature importance.
Compared against the benchmark, the proposed weight transfer model showed statistically significant gains in prediction accuracy (between 1% and 5%) as well as computation time (up to 2 hours saved) for some target domains.
The proposed method provides an adaptable clinical decision support system for hospital management that can facilitate processes of data access via the ethical committee, computation infrastructures and time.

**Keywords: Length of Stay; Time Series prediction; Domain adaptation; LSTM; SHAP feature explainability**

![image](https://github.com/LyzeNaomi/Domain-Adaptation-for-LoS-prediction/assets/70583050/f8afa079-b1f1-49c5-920e-d6da75645e67)


![image](https://github.com/LyzeNaomi/Domain-Adaptation-for-LoS-prediction/assets/70583050/51b35083-0179-4a63-99df-db0e10265016)


**Installation**
``` pip install ```

**How to cite LoS-HM-DA**

```
@article{MOMO2024108088,
title = {Length of stay prediction for hospital management using domain adaptation},
journal = {Engineering Applications of Artificial Intelligence},
volume = {133},
pages = {108088},
year = {2024},
issn = {0952-1976},
doi = {https://doi.org/10.1016/j.engappai.2024.108088},
url = {https://www.sciencedirect.com/science/article/pii/S095219762400246X},
author = {Lyse Naomi Wamba Momo and Nyalleng Moorosi and Elaine O. Nsoesie and Frank Rademakers and Bart {De Moor}}} ```
