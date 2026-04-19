## Section 1: Software and Platform
- Python
- Google Colab

### Required Python Packages
- torch
- torchvision
- numpy
- pandas
- matplotlib
- scikit-learn
- Pillow
- os
- pathlib

## Section 2: Map of Documentation
DATA Folder

- dataset link - Link to the website from which our dataset can be downloaded
- Data_Appendix.pdf – Data appendix describing variables 

SCRIPTS Folder
- flower_classification_code.ipynb - Code for exploratory plots and models 

OUTPUT Folder
- Output.pdf - Document containing all visualizations and table outputs

## Section 3: Instructions for Reproducing Results
To reproduce the results, first clone this repository and keep the folder structure unchanged. This project was developed in Python using Google Colab (but can also run in Jupyter Notebook) and requires packages such as PyTorch, torchvision, numpy, matplotlib, seaborn, Pillow, scipy, and scikit-learn. Next, download the Oxford 102 Flowers dataset from the official source linked in the repository. Upload the image file and ensure the metadata files are placed in the correct directories without renaming them. Make sure all file paths in the notebook match your environment. Then, run flower_classification_code.ipynb from top to bottom. The notebook performs data preprocessing, exploratory analysis, dataset splitting, and trains two models (EfficientNetB0 and ResNet50). It then evaluates model performance using test data and produces accuracy metrics, confusion matrices, and prediction visualizations. Reproduction is successful if the notebook runs without errors and generates the same evaluation metrics and plots as shown in the project results.

## References
[1] Visual Geometry Group, University of Oxford, “102 Category Flower Dataset,” 2008. [Online]. Available: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html.  [Accessed: Apr. 1, 2026].

[2] J. Hu, “Flower Pictures Recognition Based on the Advanced Convolutional Neural Network with Oxford Flowers 102 Dataset,” Procedia Computer Science, 2024. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S1877050924006768.  [Accessed: Apr. 1, 2026].

[3] M.-E. Nilsback and A. Zisserman, “Automated Flower Classification over a Large Number of Classes,” 2008. [Online]. Available: https://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/.  [Accessed: Apr. 1, 2026].

