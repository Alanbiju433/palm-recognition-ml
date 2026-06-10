# 🖐️ Palm Recognition ML

A machine learning project for palm/hand recognition using image classification techniques. The dataset consists of augmented palm images used to train and evaluate a recognition model.

## ✨ Features

- Palm image dataset with data augmentation
- Noise injection for robustness testing (`add_noise_to_unknown.py`)
- Image preprocessing pipeline
- Augmented dataset with varied lighting and orientation
- Scalable structure for adding more palm samples

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV / PIL | Image processing |
| NumPy | Numerical operations |
| scikit-learn / TensorFlow | ML model training |
| Jupyter Notebook | Experimentation |

## 📁 Project Structure

```
palm-recognition-ml/
├── add_noise_to_unknown.py   # Adds noise to unknown samples for robustness
├── README.md
└── dataset/                  # Augmented palm images (aug_*.jpg)
    ├── aug_0_1057.jpg
    ├── aug_0_1077.jpg
    └── ...
```

## ⚙️ Setup & Usage

1. Clone the repository
   ```bash
   git clone https://github.com/Alanbiju433/palm-recognition-ml.git
   cd palm-recognition-ml
   ```

2. Install dependencies
   ```bash
   pip install opencv-python numpy scikit-learn
   ```

3. Run noise augmentation
   ```bash
   python add_noise_to_unknown.py
   ```

## 📊 Dataset

The dataset contains augmented palm images following the naming convention `aug_{class}_{index}.jpg`. Data augmentation techniques applied include:

- Gaussian noise injection
- Rotation and flipping
- Brightness and contrast variation

## 🎯 Goal

Build a robust palm recognition system that can correctly identify individuals from palm images, even under varied conditions.

## 👤 Author

**Alanbiju433** — [GitHub Profile](https://github.com/Alanbiju433)

---

> A computer vision project exploring biometric palm recognition with ML.
