Optimal Feature Set Extraction Technique for Enhanced Medical Image Classification

- To frame the image classification problem as a weakly supervised Multiple Instance Learning problem.
- To implement an Attention based MIL model for extracting the discriminating feature in the given histopathological image.
- To test the efficiency of stain normalization by testing it with an attention based MIL model.

CHALLENGES

- These histopathology images are bound to suffer discrepancy across the images due to many factors.
- Staining tissues using Hematoxylin and Eosin stains, Time taken for absorption and scanners used for digitization of the images. These dissimilarities have an impact in identifying the type of the disease. 
- This project aims to address these issues and improve the performance metrics for handcrafted feature extraction using the techniques of deep learning for better diagnosis of medical images.

DATASET

- The Breast Cancer Histopathological Image Classification (BreakHis) is composed of microscopic images of breast tumor tissue using different magnifying factors (40X, 100X, 200X, and 400X).
- The dataset BreakHis is divided into two main groups: Benign tumors and Malignant tumors
- Benign tumors are relatively “innocents”, presents slow growing and remains localized. Malignant tumor is a synonym for cancer
- The dataset currently contains four histological distinct types of benign breast tumours: adenosis (A), fibroadenoma (F), phyllodes tumour (PT), and tubular adenona (TA); and four malignant tumours (breast cancer): carcinoma (DC), lobular carcinoma (LC), mucinous carcinoma (MC) and papillary carcinoma (PC).

FUTURE WORKS

- The given model can be improved by implementing Transformer based MIL (TransMIL).
- Multiple Instance Learning ignores the correlation between different instances. To address this issue, TransMIL seeks both spatial and morphological features between the instances.
# BreastCancerClassification
