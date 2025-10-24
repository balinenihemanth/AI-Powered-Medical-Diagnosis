📋 Project Overview

The AI-Powered Medical Diagnosis System is a deep learning-based application designed to classify eye diseases using retinal images. The model leverages Convolutional Neural Networks (CNNs) to accurately detect and differentiate between multiple eye conditions such as Cataract, Diabetic Retinopathy, Glaucoma, and Normal eyes.

This project aims to assist ophthalmologists by providing automated, explainable, and reliable disease predictions from fundus images, enabling faster diagnosis and early detection.

🚀 Features

🏥 Multi-Class Disease Classification — Identifies 4 categories: Cataract, Diabetic Retinopathy, Glaucoma, and Normal.
🔍 Explainable AI (XAI) Integration — Utilizes Grad-CAM and SHAP/LIME to visualize and interpret model predictions.
📊 High Accuracy CNN Model — Achieved ~85% accuracy on the ODIR-5K dataset.
🧩 Custom Data Preprocessing — Includes image resizing, normalization, and train/validation/test split automation.
☁️ Google Drive Integration — Dataset and model pipeline implemented using Google Colab for easy execution.

🧰 Tech Stack

Languages: Python
Libraries: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, SHAP, Grad-CAM
Dataset: ODIR-5K (Ocular Disease Intelligent Recognition)
Environment: Google Colab

⚙️ Workflow

Dataset Preparation – Sorting and organizing ODIR dataset into train/validation/test splits.
Model Training – Building and training CNN architecture on preprocessed retinal images.
Evaluation – Measuring model accuracy and performance metrics.
Explainability – Applying Grad-CAM and SHAP for model interpretation.
Visualization – Displaying results through heatmaps and interpretable plots.

