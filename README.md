# 🧠 Melanoma Classification Using CNNs

A deep learning project focused on accurately classifying melanoma skin cancer images using convolutional neural networks (CNNs). We leverage a custom CNN along with fine-tuned VGG and ResNet models, and use ensemble learning to achieve high accuracy.

---

## 📁 Dataset

- **Source:** [Kaggle: Melanoma Classification Challenge](https://www.kaggle.com/)
- Includes dermatoscopic images labeled as melanoma or non-melanoma.
- Preprocessed for uniform image size, normalization, and augmentation.

---

## 🧪 Models Used

### 1. 🔧 Custom CNN
- Built from scratch using convolutional, pooling, and dense layers.
- Acts as a baseline model.

### 2. 🧠 VGG (Fine-Tuned)
- Pretrained on ImageNet, fine-tuned on melanoma data.
- Modified final layers for binary classification.

### 3. 🔬 ResNet (Fine-Tuned)
- ResNet-50 or ResNet-101 used with transfer learning.
- Adapted last layers to focus on melanoma detection.

---

## 🤝 Ensemble Learning
- Combines predictions from all three models.
- Ensemble strategy: Majority voting / Averaged probabilities.
- Significantly boosts performance.

---

## 📊 Results

| Model       | Accuracy |
|-------------|----------|
| Custom CNN  | XX%      |
| VGG         | XX%      |
| ResNet      | XX%      |
| **Ensemble**    | **98%**     |

- Achieved up to **98% accuracy** with the ensemble approach.
- Detailed metrics (precision, recall, F1-score) available in the report.

---

## 🧰 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebooks**

---

## 📂 Folder Structure

```bash
melanoma-cnn/
├── data/                 # Dataset and preprocessing scripts
├── models/               # Saved model weights
├── notebooks/            # Jupyter notebooks for each experiment
├── src/                  # Training scripts and utility functions
├── results/              # Plots, evaluation metrics
├── README.md
├── requirements.txt
