**Auto-image Annotation using AutoDistil**
=====================================

This project demonstrates the use of AutoDistil, a self-supervised learning framework, for auto-image annotation. The goal is to annotate images without manual labeling, enabling efficient and scalable image classification tasks.

**Overview**
----------

In this project, we utilize AutoDistil to learn a shared representation space between images and their corresponding annotations. The framework leverages a contrastive loss function to encourage the model to learn a common representation space between the input images and their annotations. This allows the model to predict annotations for unseen images without requiring explicit labeling.

**Key Features**

* Auto-image annotation using AutoDistil
* Contrastive loss function for learning a shared representation space
* Scalable and efficient image classification using auto-annotated images

**Getting Started**
----------------

1. Clone the repository: git clone https://github.com/arunrajuamrutha/Auto-Image-Annotation-
2. Install the required dependencies: `pip install -q autodistill autodistill-grounded-sam autodistill-yolov8 roboflow supervision==0.9.0`
3. Run the Jupyter Notebook: `jupyter notebook`
4. Open the `Auto_image_Annotation_using_autodistil.ipynb` notebook and follow the instructions

**Architecture**
--------------

The auto-image annotation approach involves the following components:

1. **Feature Extraction**: The input images are processed using a convolutional neural network (CNN) to extract relevant features.
2. **Label Prediction**: The extracted features are then used to predict the labels for the images using a classification neural network.
3. **Post-processing**: The predicted labels are then post-processed to refine the annotations.

**Evaluation**
------------

The performance of the auto-image annotation approach is evaluated using various metrics such as accuracy, precision, recall, and F1-score.

**Results**
---------

The results of the auto-image annotation approach are presented in the `results` directory.

**Future Work**
--------------

Future work includes:

* Improving the accuracy of the auto-image annotation approach
* Exploring other applications of auto-image annotation
* Investigating the use of transfer learning for auto-image annotation


