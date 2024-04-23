# LLMs_Explainable_Feature_Engineering

This project develops machine learning (ML) models to predict cancer survivability with a focus on fairness and explainability, using data from the <a href="https://seer.cancer.gov/data/" target="_blank">SEER</a>. It addresses the need for tailored predictions that consider the different stages of several cancers, particularly bladder, breast, and prostate cancers.

## Abstract

Machine learning (ML) are demonstrating remarkable success in a variety of healthcare applications, ranging from diagnostic support and shared decision-making to personalized treatment and patient outcomes. The success of ML in healthcare is inherently linked to the rigorous process of feature engineering and feature selection, which truly form the backbone of ML model development. The main objectives of this study are to investigate the role of large language models (LLMs), and in particular ChatGPT 3.5, in the feature selection and ranking processes as a part of ML explainability within the healthcare domain. The study aims to explore how these computational models can contribute to the feature engineering process and enhance the understanding of feature importance utilizing healthcare datasets. To conduct an exploration of ChatGPT 3.5's potential in feature engineering, this study leverages two distinct datasets, including <a href="https://seer.cancer.gov/data/" target="_blank">SEER</a> dataset as well as the <a href="https://www.facs.org/quality-programs/data-and-registries/acs-nsqip//" target="_blank">NSQIP</a>, as two widely-used and well-established healthcare datasets. This contribution also runs a comparative study to compare the performance of ChatGPT 3.5 with traditional ML-based feature engineering methods, such as Information Gain (IG), Correlation-based Feature Selection (CFS), and Principal Component Analysis (PCA). The current study involves employing ChatGPT 3.5 to aid in the selection of the most important features and classification using these features. The methods will focus on understanding how ChatGPT 3.5 can be integrated into the feature engineering pipeline to improve the interpretability and explainability of ML models in healthcare. 

## Installation

To set up this project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/pitthexai/ML_Fairness_Explainability_Cancer_Survivability.git
pip install -r requirements.txt
```

## Usage
(TODO)

## Features
+ <strong>Fairness Integration:</strong> Applies fairness algorithms to ensure unbiased predictions across different patient demographics. <br>
+ <strong>Explainability Tools:</strong> Utilizes SHAP and LIME to provide insights into the decision-making process of the models. <br>
+ <strong>Stage-Specific Predictions:</strong> Trains separate models for different cancer stages to enhance prediction accuracy.


## License
Apache-2.0 license
<p><strong>Note:</strong> All ML/AI fairness parts of our code, implementation, and documentation are derived from the <a href="https://aif360.res.ibm.com/" target="_blank">AI Fairness 360 - IBM</a> package and is subject to the terms of the Apache License 2.0.</p>

## Collaborators
+ <a href="" target="_blank">Tejasvi Sanjay Kamble</a>
+ <a href="" target="_blank">Hongtao Wang</a>
+ <a href="" target="_blank">Nicole Myers</a>, RN
+ <a href="" target="_blank">Leah Reid</a>, MD
+ <a href="https://www.nursing.pitt.edu/person/young-ji-lee" target="_blank">Young Ji Lee</a>, PhD
+ <a href="https://amiielab.github.io" target="_blank">Soheyla Amirian</a>, PhD
+ <a href="https://littlefieldnick.github.io/" target="_blank">Nickolas Littlefield</a>, MS
+ <a href="https://sbmi.uth.edu/faculty-and-staff/hongfang-liu.htm" target="_blank">Hongfang Liu</a>, PhD
+ <a href="https://pitthexai.github.io/people.html" target="_blank">Liron Pantanowitz</a>, MD, PhD
+ <a href="https://www.pitt.edu/pittwire/accolades-honors/hooman-rashidi-becomes-associate-dean-ai-medicine" target="_blank">Hooman Rashidi</a>, MD
+ <a href="https://pitthexai.github.io" target="_blank">Ahmad P. Tafti</a>, PhD, FAMIA

## Citation
<p align="justify">This contribution is fully explained in the following manuscript, which is under review now at the <a href="https://eccb2024.fi/" target="_blank">ECCB 2024</a>. Any publication using this GitHub repo would require to cite the following work:
<p align="justify">
<strong>[1]</strong> Kamble et al. Machine Learning Fairness and Explainability in Stage-Specific Cancer Survivability Prediction. ECCB 2024. (Under Review now)</p>

## Contact Information
For any queries, reach out to Ahmad P. Tafti (tafti.ahmad@pitt.edu).
