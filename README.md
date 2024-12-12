# CSCI2470_Final_project
Image Captioning with Adaptive attention mechanism and user feedback

Overview
This project implements an image captioning system using deep learning techniques, specifically leveraging an adaptive attention mechanism and user feedback. 
The goal is to generate accurate and contextually relevant captions for images, enhancing the understanding of visual content through natural language.

Features
Adaptive Attention Mechanism: The model incorporates channel-wise, spatial-wise, and domain attention units to improve feature representation.
User Feedback Integration: A human-in-the-loop system allows users to provide feedback on generated captions, enhancing model performance through reinforcement learning.
Beam Search Decoding: The caption generation process utilizes beam search to explore multiple possible sequences for improved accuracy.
Visualization: The system visualizes attention weights alongside generated captions to provide insights into the model's focus during captioning.

Model Architecture
The architecture consists of two main components:
Encoder: A pre-trained CNN (ResNet-50) extracts features from input images.
Decoder: An LSTM network generates captions word by word, enhanced with an adaptive attention mechanism that dynamically adjusts focus based on input data.

Attention Mechanism
The adaptive attention mechanism includes:
Channel-wise Attention: Emphasizes important channels in the feature map.
Spatial-wise Attention: Focuses on specific regions of the image.
Domain Attention: Combines channel-wise and spatial-wise features adaptively.

THIS PROJECT USES THE COCO Dataset
