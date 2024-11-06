## RCNN (Region-based Convolutional Neural Network) from Scratch
This project implements a Region-based Convolutional Neural Network (RCNN) model from scratch using TensorFlow and Keras. RCNNs are powerful for object detection tasks, as they combine a CNN backbone for feature extraction, a Region Proposal Network (RPN) for proposing potential object regions, and classification and bounding box regression heads for final predictions.

# Key Features
Backbone Feature Extractor: Uses a pre-trained ResNet50 network to extract rich, spatial features from input images, making it adaptable for detecting objects in different contexts.
Region Proposal Network (RPN): A custom RPN built with convolutional layers to generate region proposals. It includes:
Objectness Score: Determines the likelihood of an object being present in each region.
Bounding Box Adjustments: Refines proposed bounding boxes for better localization.
ROI Pooling: Placeholder implementation using global average pooling to simplify region-specific feature aggregation.
Classification and Regression Heads: Fully connected layers for object classification and bounding box regression:
Classification Head: Predicts the object class among predefined categories.
Bounding Box Regressor: Refines the final bounding boxes for accurate object localization
