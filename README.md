🔍 Problem Statement

Given a dataset of clothing product images, the task is to detect the main product in the image and then predict multiple visual attributes that describe the product (e.g., sleeve type, neckline, color, pattern).
🛠️ Project Highlights
🔎 YOLOv5 for Object Detection
Used YOLOv5 to detect and crop the clothing region from noisy product images.

🧠 ViT (Vision Transformer) for Attribute Classification
Applied Vision Transformer (ViT) to classify multiple attributes from the cropped product images.

📁 Multi-label Classification
Predicted up to 10 different attributes per image using a multi-output head.

🧹 Data Preprocessing
Handled zip files, cleaned annotations, cropped and saved image regions for faster training.

🚀 Built in Google Colab
Optimized for Colab GPU runtime with support for saving models to Google Drive.

📦 Tech Stack
Python, PyTorch

YOLOv5, Vision Transformer (ViT)

Pandas, NumPy, OpenCV

Google Colab, Matplotlib

