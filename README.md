🧠 Brain Tumor Classification using Deep Learning

This project uses a Convolutional Neural Network (CNN) to classify brain MRI scans into four categories: Glioma, Meningioma, Pituitary, and No Tumor. The aim is to automate MRI analysis and assist radiologists in early and accurate tumor detection.

📂 Dataset

· ~3,200 MRI images across 4 classes.

· Dataset split into training, validation, and testing sets.

· Preprocessing steps included resizing, normalization, and augmentation (rotation, flipping, zooming).

🔧 Tech Stack

· Languages: Python

· Frameworks/Libraries: TensorFlow, Keras, NumPy, OpenCV, Matplotlib

· Training Setup:

  ·Optimizer: Adam

  · Loss: Categorical Crossentropy

  · Epochs: 20

  · Validation Split: 10%

  · Batch Size: Default

· Hardware: GPU (Google Colab / Local GPU)

📊 Results

· Training Accuracy: 94.77%

· Validation Accuracy: 85.88%

· Training Loss: 0.1485

· Validation Loss: 0.5185

· Visualized accuracy and loss curves for training vs validation.

🚀 Features

· Custom CNN architecture for multi-class classification.

· Data augmentation to reduce overfitting.

· Model evaluation using accuracy and loss plots.

· Addresses MRI variability challenges.

🔮 Future Improvements

· Apply Transfer Learning (ResNet, EfficientNet, VGG).

· Explore 3D CNNs for volumetric MRI data.

Implement tumor segmentation with U-Net.

Deploy as a web or mobile app for real-time usage.
