
---

**Eye Disease Classification**

This project focuses on developing a deep learning model to classify retinal images for the early detection of eye diseases. Using image datasets of the retina, it applies convolutional neural networks (CNNs) to predict the presence of conditions such as diabetic retinopathy and glaucoma.

**Project Overview**
Early diagnosis of eye diseases is crucial for timely treatment and vision preservation. This project leverages computer vision techniques to automate the classification process from retinal images.

The primary components of the project include:

* Image preprocessing
* Model training and evaluation
* Performance visualization
* Deployment-ready architecture

**Folder Structure**

* DR.ipynb: Main Jupyter Notebook for training and evaluation
* spiral.py: Data visualization using spiral plots
* colored\_images/: Sample retinal images (classified by disease stage)
* model/: Saved model files (optional)
* requirements.txt: Required Python libraries
* README.md: Project documentation

**Setup Instructions**

1. Clone the repository:
   git clone [https://github.com/YoshitaPunnati/eye-disease-classification.git](https://github.com/YoshitaPunnati/eye-disease-classification.git)
   cd eye-disease-classification

2. Set up a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate (On Windows: venv\Scripts\activate)

3. Install dependencies:
   pip install -r requirements.txt

4. Run the notebook:
   Open DR.ipynb in Jupyter Notebook or any IDE supporting notebooks.

**Model Details**

* Architecture: CNN with multiple convolutional + pooling layers
* Loss Function: Categorical Crossentropy
* Optimizer: Adam
* Metrics: Accuracy, Confusion Matrix, ROC-AUC (optional)
* Augmentation: Horizontal flip, rotation, zoom, etc. (via ImageDataGenerator)

**Results**


* Visualizations include:

  * Training vs Validation loss/accuracy
  * Confusion matrix
  * Misclassified examples


