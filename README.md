This repository contains the complete codebase for the implementation of my master's thesis conducted at Dalhousie University. The thesis is titled **"[ME-IDS: An Ensemble Transfer Learning Framework Based on Misclassified Samples for Intrusion Detection Systems.](https://dalspace.library.dal.ca/handle/10222/83178)"**

## Abstract of the Thesis
In our digitally interconnected world, the demand for robust security measures has become increasingly apparent, given the escalating threat of cyberattacks on the Internet. Intrusion Detection Systems (IDS) have emerged as vital safeguards for Internet network infrastructure. Despite the significant advancements in IDS over the past decades, there remains much room for improvement, especially with recent advances in machine learning and deep learning. In this paper, we propose a Misclassified sample based Ensemble transfer learning framework for IDS (ME-IDS) in order to effectively detect malicious intrusions. Technically, ME-IDS employs frequency encoding to handle categorical features and utilizes a feature selection method to mitigate the curse of dimensionality. In addition, it leverages three hyper-parameter-tuned variants of a transfer learning model in its ensemble learning stage, ultimately resulting in high detection accuracy. Our experimental results based on a publicly available IDS dataset, UNSW-NB15, indicate that ME-IDS leads to an impressive accuracy of 99.72%, significantly outperforming the state-of-the-art detection systems. 

**<p align="center">Figure 1: System architecture of proposed ME-IDS framework.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/ME-IDS%20Framework.jpg" width="450" />
</p>

**<p align="center">Figure 2: Generated RGB image samples from tabular data: (a) normal flow; (b) attack flow.</p>**
<p align="center">
<img src="https://github.com/arkog96/Weighted-Ensemble-Transfer-Learning-based-Intrusion-Detection-System-/blob/main/Figures/Generated%20RGB%20Images.jpg" width="450" />
</p>
