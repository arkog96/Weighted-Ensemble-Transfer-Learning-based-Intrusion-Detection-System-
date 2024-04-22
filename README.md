This repository contains the complete codebase for the implementation of my master's thesis conducted at Dalhousie University. The thesis is titled **"[ME-IDS: An Ensemble Transfer Learning Framework Based on Misclassified Samples for Intrusion Detection Systems.](https://dalspace.library.dal.ca/handle/10222/83178)"**

## Abstract of the Thesis
In our digitally interconnected world, the demand for robust security measures has become increasingly apparent, given the escalating threat of cyberattacks on the Internet. Intrusion Detection Systems (IDS) have emerged as vital safeguards for Internet network infrastructure. Despite the significant advancements in IDS over the past decades, there remains much room for improvement, especially with recent advances in machine learning and deep learning. In this paper, we propose a Misclassified sample based Ensemble transfer learning framework for IDS (ME-IDS) in order to effectively detect malicious intrusions. Technically, ME-IDS employs frequency encoding to handle categorical features and utilizes a feature selection method to mitigate the curse of dimensionality. In addition, it leverages three hyper-parameter-tuned variants of a transfer learning model in its ensemble learning stage, ultimately resulting in high detection accuracy. Our experimental results based on a publicly available IDS dataset, UNSW-NB15, indicate that ME-IDS leads to an impressive accuracy of 99.72%, significantly outperforming the state-of-the-art detection systems. 

**<p align="center">Figure 1: System architecture of proposed ME-IDS framework.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/ME-IDS%20Framework.jpg" width="450" />
</p>

**<p align="center">Figure 2: Generated RGB image samples from tabular data: (a) normal flow; (b) attack flow.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/Generated%20RGB%20Images.jpg" width="400" />
</p>

**<p align="center">Figure 3: Feature Significance Analysis Using Chi-Square p-Value.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/Chi-square.jpg" width="500" />
</p>

## Performance Evaluation 
The performance of the proposed ME-IDS framework is assessed against three benchmark ensemble methods, namely Stacked Ensemble, Concatenation Ensemble, and Confidence Averaging, as well as the three base classifiers used in the proposed weighted ensemble schemes within the framework.

| Method          | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
|-----------------:|:----------:|:----------:|:----------:|:----------:|
| Stacked Ensemble| 85.85    | 87.47     | 84.75  | 85.29    |
| Concatenation Ensemble| 95.31 | 96.07     | 94.78  | 95.20    |
| Confidence Averaging   | 97.72 | 97.96     | 97.50  | 97.69    |
| VGG16-SA        | 98.72    | 98.79     | 98.63  | 98.70    |
| VGG16-TPE       | 99.15    | 99.17     | 99.11  | 99.14    |
| VGG16-RS        | 99.43    | 99.43     | 99.43  | 99.43    |
| ME-IDS          | 99.72    | 99.74     | 99.68  | 99.71    |

**<p align="center">Figure 4: Performance improvement of ME-IDS compared to base classifiers and three benchmark ensemble methods using selected features.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/Performance%20Improvement.jpg" width="450" />
</p>

