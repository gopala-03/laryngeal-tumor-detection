# Laryngeal Tumor Detection using Deep Learning

## Overview
This repository focuses on the early detection of laryngeal tumors, a potentially life-threatening condition, using advanced deep learning techniques. Laryngeal tumors, whether benign or malignant, demand timely intervention for improved patient outcomes. The proposed model employs Convolutional Neural Networks (CNNs) to automatically identify laryngeal tumors in medical images, offering an efficient and accurate diagnostic approach.

## Methodology
In this a comprehensive methodology is employed for early laryngeal tumor detection using deep learning. Beginning with data collection, the dataset is meticulously curated, comprising distinct categories of tumor and non-tumor images. The image preprocessing stage involves crucial steps like contour cropping, grayscale conversion, Gaussian blur, thresholding, and resizing. The dataset is strategically split into training, validation, and test sets for effective model development. The deep learning model, constructed using TensorFlow and Keras libraries, incorporates convolutional layers for image feature extraction. Training involves utilizing the Adam optimizer and binary cross-entropy loss, allowing the model to distinguish between laryngeal tumor and non-tumor images. Evaluation metrics, including loss and accuracy, provide insights into the model's generalization to new data. The model's effectiveness is further assessed through predictions on the test dataset, computing the F1 score for balanced performance measurement. Finally, the trained model is saved for potential integration into clinical applications or further research, showcasing a robust and systematic approach to laryngeal tumor detection.

## Dataset Used
A meticulously curated dataset comprising 28 images, including 24 laryngeal tumor images and 4 images of a healthy larynx. Overcoming limitations of publicly available datasets, this collection ensures real-world relevance.

The development of a deep learning model for early laryngeal tumor detection, emphasizes the critical need for timely intervention. Leveraging CNNs, the model showcases capabilities that could revolutionize clinical practices, offering an automated and efficient alternative to manual examination.
