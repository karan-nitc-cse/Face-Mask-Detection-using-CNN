# Face Mask Detection Using MobileNetV2 and OpenCV

## 🚀 Overview

Face mask detection has become an essential tool for maintaining public safety, especially during health crises like the COVID-19 pandemic. This project employs **MobileNetV2** and **OpenCV** to create an efficient and lightweight face mask detection system capable of real-time analysis. 

The system identifies whether a person is wearing a mask or not, using deep learning techniques combined with computer vision.

---

## 🌟 Features

- **Real-Time Mask Detection**: Analyze live video streams or static images to detect face masks.
- **Lightweight & Efficient**: Powered by MobileNetV2 for fast and accurate predictions.
- **Customizable**: Easily retrain the model with new datasets or modify detection thresholds.
- **Pre-Trained Model Support**: Use our pre-trained weights for instant testing.

---

## 📂 Dataset

The dataset consists of labeled images divided into two classes:
- **With Mask**: Images showing individuals wearing face masks.
- **Without Mask**: Images of individuals without face masks.

### Preprocessing Steps:
- Images resized to **128x128 pixels**.
- Normalized pixel values for faster convergence.
- Data augmentation applied for better model generalization.

---

## 🔧 Model Architecture

The core of the system is **MobileNetV2**, chosen for its balance of performance and computational efficiency. Key components include:
- **Feature Extraction**: MobileNetV2 base for extracting rich image features.
- **Dense Layers**: Fully connected layers for classification into "With Mask" or "Without Mask."
- **Input Size**: Images of size **128x128x3 (RGB)**.

---

## 🚧 Installation and Setup

### Prerequisites
Ensure the following are installed on your system:
- Python 3.8+
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

### Steps to Set Up

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd face-mask-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Prepare the dataset:
   - Place the dataset in the `data/` directory.
   - Ensure the folder structure follows:
     ```
     data/
     ├── train/
     │   ├── with_mask/
     │   └── without_mask/
     ├── test/
     │   ├── with_mask/
     │   └── without_mask/
     ```

---

## 🎮 Usage

### 1. Train the Model
Train the model using your dataset:
```bash
python train.py
```

### 2. Evaluate the Model
Test the model’s performance on the validation or test set:
```bash
python evaluate.py
```

### 3. Real-Time Detection
Run real-time detection using your webcam or video file:
```bash
python detect_mask_video.py
```

---

## 📊 Results

- **Accuracy**: Achieved **XX%** accuracy on the test set.
- **Model Size**: The final model is lightweight and optimized for deployment.

### Sample Output

Include a few sample detections for better visualization:

| Input Image | Prediction |
|-------------|------------|
| ![with_mask](https://via.placeholder.com/100) | Mask Detected |
| ![without_mask](https://via.placeholder.com/100) | No Mask Detected |

---

## 📁 Project Structure

```
face-mask-detection/
├── data/                     # Dataset directory
├── models/                   # Trained model weights
├── scripts/                  # Scripts for training, evaluation, and detection
├── requirements.txt          # Dependencies
├── train.py                  # Model training script
├── evaluate.py               # Model evaluation script
├── detect_mask_video.py      # Real-time detection script
└── README.md                 # Documentation
```

---

## 🛠️ Future Enhancements

- **Multi-Class Detection**: Expand to detect improper mask usage.
- **Model Optimization**: Optimize for edge devices like Raspberry Pi.
- **Enhanced Dataset**: Incorporate more diverse and challenging samples.

---

## 🤝 Contributing

Contributions are welcome! Whether it’s fixing bugs, improving documentation, or enhancing the model, feel free to:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

## 🐝 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 💬 Acknowledgments

Special thanks to:
- **MobileNetV2**: Lightweight architecture by Google.
- **OpenCV**: For robust video and image processing.
- Contributors who made the dataset publicly available.

---
