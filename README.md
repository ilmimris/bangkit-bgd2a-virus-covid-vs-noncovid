# FINAL PROJECT - BANGKIT | BDG2-A

# DATASET REPOSITORY 1
### LINK SOURCE
#### Covid Chestxray Dataset
    https://github.com/ieee8023/covid-chestxray-dataset
    
#### 🛑 Note: please do not claim diagnostic performance of a model without a clinical study! This is not a kaggle competition dataset. Please read this paper about evaluation issues: https://arxiv.org/abs/2004.12823 and https://arxiv.org/abs/2004.05405

#### COVID-19 image data collection
Project Summary: To build a public open dataset of chest X-ray and CT images of patients which are positive or suspected of COVID-19 or other viral and bacterial pneumonias (MERS, SARS, and ARDS.). Data will be collected from public sources as well as through indirect collection from hospitals and physicians. All images and data will be released publicly in this GitHub repo.


This project is approved by the University of Montreal's Ethics Committee #CERSES-20-058-D

#### View current images and metadata
Current stats of PA, AP, and AP Supine views. Labels 0=No or 1=Yes. 

    COVID19_Dataset num_samples=408 views=['PA', 'AP']
    {'ARDS': {0.0: 393, 1.0: 15},
     'Bacterial Pneumonia': {0.0: 379, 1.0: 29},
     'COVID-19': {0.0: 96, 1.0: 312},
     'Chlamydophila': {0.0: 407, 1.0: 1},
     'Fungal Pneumonia': {0.0: 395, 1.0: 13},
     'Influenza': {0.0: 407, 1.0: 1},
     'Klebsiella': {0.0: 401, 1.0: 7},
     'Legionella': {0.0: 404, 1.0: 4},
     'Lipoid': {0.0: 405, 1.0: 3},
     'MERS': {0.0: 408},
     'Mycoplasma': {0.0: 404, 1.0: 4},
     'No Finding': {0.0: 393, 1.0: 15},
     'Pneumocystis': {0.0: 395, 1.0: 13},
     'Pneumonia': {0.0: 17, 1.0: 391},
     'SARS': {0.0: 392, 1.0: 16},
     'Streptococcus': {0.0: 395, 1.0: 13},
     'Varicella': {0.0: 404, 1.0: 4},
     'Viral Pneumonia': {0.0: 75, 1.0: 333}}

    COVID19_Dataset num_samples=134 views=['AP Supine']
    {'ARDS': {0.0: 133, 1.0: 1},
     'Bacterial Pneumonia': {0.0: 134},
     'COVID-19': {0.0: 12, 1.0: 122},
     'Chlamydophila': {0.0: 134},
     'Fungal Pneumonia': {0.0: 134},
     'Influenza': {0.0: 134},
     'Klebsiella': {0.0: 134},
     'Legionella': {0.0: 134},
     'Lipoid': {0.0: 134},
     'MERS': {0.0: 134},
     'Mycoplasma': {0.0: 134},
     'No Finding': {0.0: 130, 1.0: 4},
     'Pneumocystis': {0.0: 134},
     'Pneumonia': {0.0: 8, 1.0: 126},
     'SARS': {0.0: 134},
     'Streptococcus': {0.0: 134},
     'Varicella': {0.0: 134},
     'Viral Pneumonia': {0.0: 12, 1.0: 122}}

###### FOR INFORMATION ABOUT DATASET CONTINUE IN LINK SOURCE DATASET REPOSITORY 1

# DATASET REPOSITORY 2

### LINK SOURCE
#### Chest X-Ray From Kaggle 
    https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
    
### CONTEXT 
http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

The normal chest X-ray (left panel) depicts clear lungs without any areas of abnormal opacification in the image. Bacterial pneumonia (middle) typically exhibits a focal lobar consolidation, in this case in the right upper lobe (white arrows), whereas viral pneumonia (right) manifests with a more diffuse ‘‘interstitial’’ pattern in both lungs.
http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### CONTENT

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

### ACKNOWLEDGMENTS
- Data: https://data.mendeley.com/datasets/rscbjbr9sj/2
- License: CC BY 4.0
- Citation: http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

### METADATA 
    Usage Information             License                     Other (specified in description)
                                  Visibility                  Public

    Maintainers                   Dataset owner               Paul Mooney(Kaggle)

    Updates                       Expected update frequency   Not specified
    
    Last updated                  2018-03-25                  Date created
                                  2018-03-22                  Current version
                                                              Version 2
                                                             
