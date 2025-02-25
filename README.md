# Fruits-and-Vegetables-Deep-Learning-Classifier

This Jupyter Notebook implements a deep learning-based classification system for fruits and vegetables using a Convolutional Neural Network (CNN) enhanced with transfer learning from MobileNetV2. The model accurately classifies 36 different types of produce and employs gradient-based class activation (Grad-CAM) visualizations to explain its decision-making process.

**Dataset:** [Fruit and Vegetable Image Recognition Dataset](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

The notebook provides an end-to-end machine learning pipeline, including:

- **Data Preparation:** Structured loading and processing of 3,861 images distributed across training, validation, and test sets.
- **Data Visualization:** Exploration of the dataset using sample images from each category.
- **Data Augmentation:** Application of techniques such as rotation, zoom, shifts, shear, and flips to improve model generalization.
- **Transfer Learning:** Leveraging MobileNetV2 pre-trained on ImageNet as a feature extractor.
- **Model Architecture:** Designing a custom classification head with dense layers optimized for produce classification.
- **Performance Evaluation:** Comprehensive analysis using accuracy metrics, loss curves, classification reports, and confusion matrices.
- **Explainable AI:** Utilizing Grad-CAM to highlight key regions in images that influence the model's predictions.

The model achieves excellent accuracy while maintaining computational efficiency, making it well-suited for deployment in agricultural, retail, or consumer applications. Overall, this project showcases how deep learning can automate and enhance the accuracy of produce classification, demonstrating practical applications of computer vision in food systems.
