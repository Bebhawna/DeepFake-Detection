# Deepfake Detection Using EfficientNetB0

This project is a complete pipeline for detecting deepfake videos using Convolutional Neural Networks (CNNs), particularly the **EfficientNetB0** architecture. It includes preprocessing of data, model training, evaluation, and real-time predictions for new uploads (images/videos).

---

## 🧠 Project Overview

This deepfake detection system:
- Extracts frames from videos
- Detects and crops faces using MTCNN
- Balances real and fake datasets
- Trains a binary classifier using EfficientNetB0
- Evaluates the model using classification metrics
- Supports prediction on both images and videos

---

## 🗂️ Project Structure

├── preprocess.py # Frame extraction, face cropping, dataset balancing 
├── train_model.py # Model architecture, training, evaluation 
├── predict.py # Load model and predict on new data
├── data/ 
│ ├── real/ # Real video/image data 
│ ├── fake/ # Fake video/image data 
│ └── faces/ # Cropped face images
├── uploads/ # User uploaded files for prediction ├
── models/ 
│ └── best_model.h5 # Trained model weights 
├── README.md # Project documentation


---

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/deepfake-detector.git
   cd deepfake-detector
   ```
## Install dependencies

```bash
pip install -r requirements.txt
```
## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

Author: Bhawna Bisht


