# YOLO8 Clothing Detection
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![Python](https://img.shields.io/badge/YOLO8-violet)

## Overview
The **YOLO8 Clothing Detection** project utilizes the YOLOv8 model to detect clothing items from various classes in images. A key feature of this project is its ability to detect all parts of a single clothing item, trained specifically on marketplace data for enhanced accuracy and relevance.

## Data

The dataset used for training the **YOLO8 Clothing Detection** model consists of a diverse collection of clothing images spanning 13 distinct classes. These images serve as the foundation for the model's learning process, enabling it to accurately identify and localize various clothing items.

### Example Images
The following images provide examples of the data used for training and evaluation:

<p align="left">
  <img src="https://github.com/StrangePineAplle/YOLO8-Clothing-Detection/blob/main/pictures/pic1.jpg" width="200" />
  <img src="https://github.com/StrangePineAplle/YOLO8-Clothing-Detection/blob/main/pictures/pic2.jpg" width="200" /> 
</p>

These examples showcase the diversity of clothing items and styles present in the dataset, ensuring that the model is exposed to a wide range of scenarios during training. The annotations and labels associated with each image enable the model to learn the distinctive features and characteristics of each clothing class.

## Features
- **Multi-Class Detection**: Detects clothing items from a comprehensive set of classes.
- **Part Detection**: Identifies all parts of a single clothing item, providing detailed insights into each detected item.
- **Marketplace Data Training**: The model is trained on a dataset sourced from online marketplaces, ensuring relevance to real-world applications.

## Classes Detected
The model recognizes the following classes of clothing and accessories:
1. Accessories
2. Bag
3. Belt
4. Dress
5. Glasses
6. Headwear
7. Outerwear
8. Pants
9. Scarf
10. Shoe
11. Shorts
12. Skirt
13. Top

## Results

### Performance Metrics
- **mAP50**: 0.866
- **mAP75**: 0.806
- **mAP50-95**: 0.778

These metrics provide a comprehensive assessment of the model's ability to accurately detect and localize clothing items in images.

The **mAP50** score of 0.866 indicates that the model achieves a high precision in detecting clothing items when using a lenient IoU threshold of 0.5. This means that the model can correctly identify and localize clothing items in most cases, even if the predicted bounding boxes do not perfectly align with the ground truth.

The **mAP75** score of 0.806 suggests that the model maintains a strong performance when using a more stringent IoU threshold of 0.75. This demonstrates the model's ability to predict bounding boxes that closely match the actual size and location of clothing items in the images.

The **mAP50-95** metric, which averages the mAP scores across IoU thresholds from 0.5 to 0.95 with a step size of 0.05, provides an overall assessment of the model's performance. The score of 0.778 indicates that the model consistently performs well across various IoU thresholds, making it suitable for practical applications where precise localization is crucial.

<p align="left">
  <img src="https://github.com/StrangePineAplle/YOLO8-Clothing-Detection/blob/main/pictures/pic3.png" />
</p>
