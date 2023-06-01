# Group024-SP23

This repository contains the code and data for the project "Classification of Mitochondrial Morphology Types: Comparative Analysis of Novel and Established Machine Learning Methodologies". The project aims to develop novel classification models for accurately identifying mitochondrial morphology types and compare them against a baseline approach. The classification models are evaluated based on their accuracy in classifying three distinct classes of mitochondria: punctate, swollen, and networked.

### Background
Accurate classification of mitochondrial morphology types is crucial for understanding cellular health and function. This project builds upon the methodology outlined in the publication "Deep Analysis of Mitochondria and Cell Health Using Machine Learning" to propose novel classification models for mitochondrial morphology classification. By comparing these models against the baseline approach, this study aims to contribute to the advancement of mitochondrial research and its implications for cellular health and function.

### Data
The microscopy data used in this project was obtained from the publication "Deep Analysis of Mitochondria and Cell Health Using Machine Learning." The dataset consists of images captured following a standardized procedure involving the application of various drug conditions. The dataset includes samples representing three distinct classes of mitochondria: punctate, swollen, and networked.

### Methodology
The baseline methodology for classifying mitochondrial morphology types involves training a K-nearest neighbors (KNN) model (k=5) and a naive Bayes classifier. These models utilize pre-engineered features described in the aforementioned publication. To evaluate the effectiveness of these models, we also employ support vector machines (SVM), decision trees, Multi-layer Perceptron (NN), ensembles, and convolutional neural networks (CNN). The evaluation is based on the classification accuracy rate, allowing for a comprehensive assessment of each model's proficiency in accurately classifying mitochondrial morphology types.

### Installation
To use the code in this repository, follow these steps:

1. Clone the repository:
```
git clone https://github.com/COGS118A/Group024-SP23.git
```
2. Install the required dependencies:

### Usage
To reproduce the experiments and run the classification models, open the Jupyter Notebook file FinalProject_Group024-SP23.ipynb in Jupyter Notebook or JupyterLab. The notebook contains detailed instructions and code for training and evaluating the classification models.

### Results
The results of the comparative evaluation between the baseline and novel classification models are presented in the Jupyter Notebook file FinalProject_Group024-SP23.ipynb. The classification accuracy rates for each model are reported, providing insights into the proficiency of the models in accurately classifying mitochondrial morphology types.

### Contributing
This repository is for educational purposes as part of the COGS 118A course. Therefore, external contributions are not expected. However, if you have any suggestions or feedback, please feel free to open an issue in the repository.

### Acknowledgments

We would like to express our gratitude to the COGS 118A teaching staff for providing guidance throughout the course.

We also acknowledge the following research paper for providing insights and inspiration for our analysis:

Zahedi, A., On, V., Phandthong, R. et al. Deep Analysis of Mitochondria and Cell Health Using Machine Learning. Sci Rep 8, 16354 (2018).\
Reference: https://doi.org/10.1038/s41598-018-34455-y

We appreciate the authors' contributions to the scientific community and their valuable research, which helped shape our approach in this project.

### Contact
If you have any questions or inquiries, please contact the members of Group024:

Colin Caban (ccaban@ucsd.edu)\
Nakshatra Bansal (nabansal@ucsd.edu)\
Momei Fang (mvfang@ucsd.edu)\
Anna Sim (asim@ucsd.edu)

Feel free to reach out to us if you have any questions related to the analysis or this repository.
