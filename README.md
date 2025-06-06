# Brain-Tumor-Detection
Aim:
To detect brain tumors from MRI images and compare the performance of a traditional Convolutional Neural Network (CNN) with a Fuzzy CNN model that combines fuzzy logic to handle uncertainty in medical images.

Tools & Technologies Used:
Python
TensorFlow / Keras
OpenCV
NumPy, Matplotlib, Seaborn
Jupyter Notebook

Kaggle Dataset (MRI brain tumor images)

Methodology:
Collaboration & Research:
Worked with a mentor and studied IEEE research papers to understand techniques used in brain tumor detection.

Data Collection & Preprocessing:
Collected MRI brain images from Kaggle.
Applied preprocessing: resizing, normalization, noise removal.
Used data augmentation (flipping, rotating, zooming) to increase dataset size and variety.

Model Building:
Trained a CNN model to classify images with/without tumors.
Built a Fuzzy CNN by integrating fuzzy logic with CNN to better manage unclear or noisy regions in images.

Model Evaluation:
Compared models using accuracy, confusion matrix, and classification reports.

CNN Accuracy: ~96%
Fuzzy CNN Accuracy: ~98%

Conclusion:
The Fuzzy CNN outperformed the traditional CNN, especially in cases where tumor boundaries were not clearly visible. Integrating fuzzy logic improved the model’s ability to deal with uncertainty, making it more reliable for real-world medical image classification.

