Trustworthy AI in Healthcare
🚀 Project Overview
This project demonstrates the principles of Trustworthy AI in the context of healthcare, focusing on skin cancer detection models. The goal is to evaluate and present the differences in model performance, fairness, and bias across different datasets. It aims to create a robust AI system that predicts melanoma from images of skin lesions while ensuring fairness, transparency, and bias mitigation.

📋 Features
Model Comparison: Two models are showcased — one with inherent bias (trained on light-skinned samples) and one bias-free (trained on grayscale images).
Bias Mitigation: Address color bias using grayscale and histogram equalization techniques.
Transparency & Fairness: Uphold ethical AI principles with an emphasis on fairness and explainability.
Interactive Visualizations: Key metrics and performance results are displayed using interactive plots.
User-Friendly UI: Intuitive and minimal user interface for an accessible experience.
📚 Problem Statement
Skin cancer, particularly melanoma, is one of the most common and deadliest types of cancer. Early detection is crucial for effective treatment. However, existing AI models often face challenges such as overfitting to certain image features, including color bias. Models trained solely on color images may perform poorly when applied to images that lack color or have different lighting conditions, leading to inaccurate or unfair predictions.

🎯 Objective
To build a trustworthy AI model that can predict the likelihood of skin cancer from images, addressing bias issues related to color variations. This is achieved through the use of two distinct models:

Model 1: Color Image-Based Model — Trained on original color images of skin lesions, detecting melanoma patterns using all color features.
Model 2: Grayscale Image-Based Model — Uses grayscale images of the lesions, removing color information. Histogram equalization is applied to ensure that the model focuses on texture, shape, and other critical features, reducing color bias.
⚙️ Approach
Model 1: Color Image-Based Model

Training Data: Original color images of skin lesions.
Focus: Uses color information, shape, and texture features to detect melanoma.
Limitation: Color bias may cause inaccurate predictions when images contain lighting variations or come from different skin tones.
Model 2: Grayscale Image-Based Model

Training Data: Grayscale images where color information is removed.
Processing: Histogram equalization is applied to normalize brightness and contrast.
Focus: Detects patterns using texture, shape, and other non-color-dependent features.
Goal: Reduce reliance on color to ensure fair predictions, especially for diverse skin tones.
🛠️ Bias Mitigation Strategy
By training both models with different image modalities, we aim to create a fairer AI system that is not overly dependent on color variations. The grayscale model serves as a critical method to ensure that the system does not favor certain skin tones, lighting conditions, or color intensities during predictions.
