# Ensemble-Deep-Learning-for-Precision-Detection-and-Severity-Assessment-of-Wheat-Diseases

🔗 Availability of Code and Dataset

Source Code (GitHub DOI): [![DOI](https://zenodo.org/badge/1104394255.svg)](https://doi.org/10.5281/zenodo.17726310)

Dataset : https://www.kaggle.com/datasets/tolgahayit/yellowrust19-yellow-rust-disease-in-wheat

Both resources are publicly available to support transparency and reproducibility.

📂 Repository Structure
├── Implementation.ipyn              # complete code with results)

└── README.md

⚙️ Dependencies

Install packages using:

pip install -r requirements.txt


Main libraries:

Python 3.8+

TensorFlow 

NumPy

OpenCV

Scikit-learn

Matplotlib

🗂 Dataset

The YELLOW-RUST-19 dataset is a comprehensive collection of wheat leaf images categorized based on the severity levels of yellow rust disease. Developed by a team of researchers from Turkey in collaboration with experts, this dataset aims to facilitate research on plant pathology using advanced deep learning methods. The data was collected from fields managed by the Republic of Turkey Ministry of Agriculture and Forestry Directorate of Field Crops Central Research Institute, located in Haymana-Ankara.

1.1 Dataset Overview
Total Images: 15,000 leaf images
Categories: Healthy and diseased (six severity levels)
Raw and Preprocessed Images: Not Included
Collection Period: October-November 2018
Field Location: Haymana-Ankara, Turkey
1.2 Severity Levels
Images are categorized into the following six classes based on infection severity:

0: No signs of infection (Healthy) - 2,500 images
R: Minor signs of infection (Resistant) - 2,500 images
MR: Small to medium signs of infection (Moderately Resistant) - 2,500 images
MRMS: Moderate infection (Moderately Resistant-Moderately Susceptible) - 2,500 images
MS: Medium infection (Moderately Susceptible) - 2,500 images
S: Major infection (Susceptible) - 2,500 images
1.3 Citation
Hayit, T., Erbay, H., Varçın, F., Hayit, F., & Akci, N. (2021). Determination of the severity level of yellow rust disease in wheat by using convolutional neural networks. Journal of Plant Pathology, 103(3), 923-934.
Hayıt, T., Erbay, H., Varçın, F. et al. (2023). The classification of wheat yellow rust disease based on a combination of textural and deep features. Multimed Tools Appl. https://doi.org/10.1007/s11042-023-15199-y

🚀 Training

To train the ensemble deep learning model:

 --epochs 05 --batch_size 32 --img_size 224

🧪 Testing / Evaluation

To evaluate the trained model test on the random Yellow rust image.

📊 Outputs

The repository generates:

Accuracy and loss curves

Confusion matrices

classification results




📝 Citation

If you use this code or dataset, please cite the manuscript:

This repository contains the official implementation of the manuscript titled
"Ensemble Deep Learning for Precision Detection and Severity Assessment of Wheat Diseases,"
submitted to *The Visual Computer*.

If you use this code or dataset in your research, please cite our manuscript.


(Full BibTeX will be added after acceptance.)

✉ Contact

For questions or collaborations:

Author: Muhammad Asim
Email: muhammadasim.IT@hu.edu.pk


