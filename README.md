# Pet classification using deep learning – IRCD Shelters

## 📋 Brief description and context

As part of a collaborative project with **"It's Raining Cats and Dogs" (IRCD) shelters**, I developed a deep learning model to address the challenge of animal identification. The shelters required a system capable of distinguishing between cats and dogs using images provided by volunteers. This initiative aimed to streamline the animal intake process and improve operational efficiency in shelters.

The project involved building, training, and evaluating a convolutional neural network (CNN) to classify images as either cats or dogs. The solution also incorporated **transfer learning** to enhance model performance, leveraging pre-trained VGG16 weights.

This work serves as a foundation for future implementations, such as recognizing specific breeds or detecting behavioral traits, further improving the shelters' capabilities in animal management and adoption processes.

---

## 🏆 Achievements

- **Custom CNN development**: Built a convolutional neural network to classify images into "Cat" or "Dog" categories.
- **Transfer learning implementation**: Integrated VGG16 pre-trained weights for efficient feature extraction and enhanced model accuracy.
- **Data augmentation**: Applied transformations to expand the dataset and prevent overfitting.
- **Recommender system design**: Developed a prototype for recommending animals to potential adopters based on user preferences and behavioral profiles.
- **End-to-End workflow**: Delivered a fully operational pipeline for data preprocessing, model training, and prediction deployment.

---

## 🎯 Responsibilities

### Needs analysis
- Collaborated with IRCD shelters to identify pain points in the animal intake and management processes.
- Defined project requirements, focusing on classification accuracy, scalability, and ease of deployment.

### System development
- Built the classification system using Python and TensorFlow.
- Implemented data augmentation techniques (rotation, scaling, flipping) to enhance model robustness.
- Designed a CNN architecture, including convolutional layers, pooling, dropout, and dense layers, to ensure reliable classification.
- Employed transfer learning with VGG16 to achieve higher accuracy with limited data.

### Evaluation and insights
- Analyzed model performance metrics, including accuracy, precision, recall, and F1-score.
- Conducted error analysis to identify and address misclassifications.
- Delivered visual reports and metrics for stakeholders to understand model effectiveness.

### Behavioral recommender system
- Proposed and prototyped a **content-based recommendation system** for matching adopters with suitable pets.
- Used cosine similarity to compare adopter preferences with animal behavioral profiles.

---

## 🛠️ Technology stack

- **Programming language**: Python  
- **Libraries**:
  - `TensorFlow` and `Keras`: For building and training deep learning models.
  - `Pandas` and `NumPy`: For data manipulation and feature engineering.
  - `OpenCV`: For image preprocessing and visualization.
  - `Matplotlib`: For performance visualization.
  - `Scikit-learn`: For performance evaluation and similarity computations.

---

## 🔍 Sample model performance metrics

| Metric       | Value |
|--------------|-------|
| Training Accuracy | 94.6% |
| Validation Accuracy | 92.3% |
| Precision (Cats)   | 0.96  |
| Precision (Dogs)   | 0.93  |
| Recall (Cats)      | 0.92  |
| Recall (Dogs)      | 0.95  |

---

## 🖥️ Key code snippets

Due to the detailed and extensive nature of the project, all code and implementation details are included in the **notebook attached to this repository**. You can access the notebook for a comprehensive overview of the model architecture, data preprocessing, and evaluation.

---

## ✨ Relevance to the i-CITY AI platform development

This project demonstrates competencies and methodologies highly relevant to developing modules for the **i-CITY AI Platform**:

1. **Data handling and automation**:
   - **Project**: Implemented end-to-end workflows for image classification, from data preprocessing to model deployment.
   - **i-CITY**: Skills transferable to automating analytics for system usage and quality monitoring.

2. **Interface and modular design**:
   - **Project**: Designed modular code for model training and evaluation, allowing seamless integration of new features.
   - **i-CITY**: Experience applicable to building scalable APIs and ensuring modular design for platform components.

3. **Scalability and adaptation**:
   - **Project**: Developed a framework adaptable to additional classes, such as specific breeds or traits.
   - **i-CITY**: Demonstrates the ability to create scalable systems for routing tasks or managing diverse agents.

By combining expertise in deep learning, transfer learning, and recommendation systems, this project highlights my ability to contribute to Staizen’s **i-CITY AI platform** development.

---
