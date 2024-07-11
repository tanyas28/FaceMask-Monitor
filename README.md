## The Project Overview
The Face Mask Detection project is developed to address the growing need for automated monitoring of face mask usage in public spaces, especially during the COVID-19 pandemic. The system aims to enhance public safety by ensuring compliance with health guidelines and mitigating the spread of infectious diseases.

This project leverages state-of-the-art deep learning techniques to accurately detect the presence of face masks on individuals in real-time. By utilizing the MobileNet architecture, which is known for its efficiency and performance, the model achieves a high accuracy rate , making it suitable for deployment in various real-world applications such as surveillance systems, access control in buildings, and public transportation monitoring.

**The key functionalities of this project include:**
- **Real-Time Detection**: The system processes live video feeds and detects face masks instantly, providing immediate feedback.
- **High Accuracy**: With a high accuracy rate, the model ensures reliable detection, reducing the chances of false positives and negatives.
- **Efficiency**: The MobileNet architecture is optimized for low computational resources, making the model lightweight and fast, suitable for edge devices.
- **Scalability**: The project can be extended and adapted to different environments and requirements, including integration with existing security systems and expansion to detect other types of protective gear.

## Features
- Real-time detection of face masks in video streams.
- High accuracy using the MobileNet CNN architecture.
- Lightweight and efficient model suitable for deployment on edge devices.
## Dataset
The dataset used for training and testing the model includes images of people with and without face masks. The dataset is split into training, validation, and test sets to evaluate the model's performance accurately.

- **Total Images**: Approximately 1900
- **Classes**: With Mask, Without Mask

## Model Architecture
The model is based on the MobileNet architecture, which is known for its efficiency and accuracy in image classification tasks. The architecture is as follows:
- Input Layer: Image of size 224x224x3
- Multiple Convolutional Layers with ReLU activation
- Depthwise Separable Convolutions
- Global Average Pooling Layer
- Fully Connected Layer with Softmax activation for binary classification

## Acknowledgments
This code is based on the [Face-Mask-Detection](https://github.com/balajisrinivas/Face-Mask-Detection) repository by [balajisrinivas](https://github.com/balajisrinivas).

