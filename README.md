
🩺 Kidney Disease Classification using Deep Learning (CT Scans)

This project focuses on the detection and classification of kidney diseases from CT scanned images using Deep Learning.
The model classifies kidney CT images into the following categories:

✅ Normal
🟠 Cyst
🔴 Tumor
🪨 Stone

----------------------------------------------------------------------------

🚀 Features

Deep Learning model based on ResNet50 architecture (transfer learning).
Dataset is split into Train (70%), Validation (15%), and Test (15%).
Training with balanced data to avoid class bias.
Evaluation metrics: Accuracy, Confusion Matrix, F1-score.
Supports single image prediction – upload a CT scan and get the classification result.

----------------------------------------------------------------------------

📂 Dataset

The dataset used is CT Kidney Dataset (Normal / Cyst / Tumor / Stone).
Organized in the following structure:

CT-KIDNEY-DATASET-Normal-Cyst-Tumor-Stone/
│── train/
│    ├── Normal/
│    ├── Cyst/
│    ├── Tumor/
│    └── Stone/
│── val/
│── test/

----------------------------------------------------------------------------

📊 Results

Training accuracy gradually improves with epochs.

Model evaluation includes:
✅ Accuracy
✅ Confusion Matrix
✅ F1 Score

----------------------------------------------------------------------------

📌 Future Work

Improve accuracy using data augmentation and fine-tuning deeper layers.
Deploy as a Flask / FastAPI web app.
Build a mobile app for real-time predictions.

-----------------------------------------------------------------------------

🤝 Contributing

Contributions are welcome!
Fork the repo
Create a new branch (feature-xyz)
Commit changes and open a PR 🚀
