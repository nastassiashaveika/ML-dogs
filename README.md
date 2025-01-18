# Paws and Pixels: My Dog's Routine Classifier 
This repository contains the implementation and evaluation of a deep learning project focused on classifying dog activities and distinguishing between breeds. The goal is to answer two main questions:

1. Can convolutional neural networks (CNNs) differentiate between my dog (a West Highland White Terrier named Ronnie) and other similar dogs?
2. Can they classify Ronnie's activities, such as sitting, lying, standing, or being with people, and distinguish between Westies and Maltese dogs?

**Key Features**

*Dataset*: Combines personal images of Ronnie and data from the Stanford Dogs Dataset. Images were preprocessed, resized to 160x160 pixels, and categorized into six classes.

*Models Used*:

- MobileNetV2: Lightweight and efficient architecture leveraging transfer learning with pre-trained ImageNet weights.
- InceptionV3: Architecturally advanced model for multi-scale feature extraction.
  
*Training Process*:

- Transfer learning and fine-tuning to optimize performance.
- Early stopping and model checkpoints to prevent overfitting and retain the best weights.
  
*Performance Metrics*:

- MobileNetV2 achieved superior accuracy (85.92%) and generalization across most classes.
- Evaluation includes confusion matrices, precision, recall, and F1-scores for both models.
  
*Results and Insights*:

- Best Performing Class: "Maltese_not Ronnie" due to distinct visual features, achieving near-perfect precision and recall.
- Challenging Classes: Activity-based classes like "Standing" and "With People," where overlapping features caused frequent misclassifications.
