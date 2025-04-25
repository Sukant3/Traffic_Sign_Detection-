# 🚦 Traffic Sign Recognization System
__________________
This research presents a deep learning-powered Traffic Sign Classification System that automatically recognizes traffic signs from images and provides corresponding road safety instructions. 

The system is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset and leverages a convolutional neural network (CNN) model optimized for traffic sign recognition efficiency. 

The interface allows users to upload an image of a traffic sign, which is then classified into one of 43 categories. Corresponding road safety guidelines are displayed for each sign.

__________________
✅ Project Overview

Implementation of a CNN model trained on the GTSRB dataset for efficient traffic sign classification.

Mapping each predicted sign category to appropriate road safety instructions.

Gradio-based user interface for practical testing and educational applications.
____________________________
🚀 Dataset Overview

Source: German Traffic Sign Recognition Benchmark (GTSRB)

Total Samples: Over 50,000 (39,209 training, 12,630 testing)

Classes: 43 (e.g., Speed limit signs, Stop sign, Yield sign)

Format: Variable-sized color images

Single-image, multi-class classification problem

Dataset Link:- https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
________________
![image](https://github.com/user-attachments/assets/56c8e396-04e8-4b7f-af5c-eb071fdeffa6)
_____________
📊 How CNN Works ?

Layer Type | Input Size | Output Size

Conv2D + ReLU | 32x32x3 | 32x32x32

MaxPool | 32x32x32 | 16x16x32

Conv2D + ReLU | 16x16x32 | 16x16x64

MaxPool | 16x16x64 | 8x8x64

Flatten | 8x8x64 | 4096

Fully Connected | 4096 | 128

Fully Connected | 128 | 43 (classes)
________
🔥 Contribution 

Feel free to contribute and Suggestion 
