# Lung Cancer Detection Using Transfer Learning Models

## 📋 Project Overview

This project implements a comprehensive deep learning solution for **lung cancer detection** using transfer learning on CT scan images. We evaluated **eight different pre-trained transfer learning models** to identify the one achieving the highest accuracy and optimal performance metrics.

**Dataset Source:** [Kaggle - Chest CT Scan Images](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)

---

## 🧠 Models Evaluated

The following transfer learning architectures were compared:

1. **ConvNext** - Latest generation convolutional neural networks
2. **EfficientNetB0** - Efficient and scalable CNN architecture
3. **VGG-16** - Classical deep CNN architecture
4. ResNet variants
5. MobileNet
6. InceptionV3
7. DenseNet
8. Xception

Each model was trained and validated on the chest CT scan dataset to compare accuracy, precision, recall, and F1-scores.

---

## 📁 Project Structure

```
Lung-cancer-detection-using-different-transfer-learning-model/
├── README.md                                      # Project documentation
├── LICENSE                                         # Apache 2.0 License
├── ConvNext-Transfer Learning Model.ipynb        # ConvNext implementation
├── EfficientNetB0-Transfer Learning Model.ipynb  # EfficientNetB0 implementation
├── VGG_16-Transfer Learning Model.ipynb          # VGG-16 implementation
└── [Additional model notebooks...]               # Other transfer learning models
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- TensorFlow / PyTorch
- NumPy, Pandas, Scikit-learn, Matplotlib

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nayon09/Lung-cancer-detection-using-different-transfer-learning-model.git
cd Lung-cancer-detection-using-different-transfer-learning-model
```

2. Install required dependencies:
```bash
pip install tensorflow numpy pandas scikit-learn matplotlib opencv-python
```

3. Download the dataset from Kaggle:
   - Visit: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
   - Download and extract the dataset

### Usage

1. Open any notebook in Jupyter:
```bash
jupyter notebook "ConvNext-Transfer Learning Model.ipynb"
```

2. Follow the notebook instructions to:
   - Load and preprocess CT scan images
   - Train the transfer learning model
   - Evaluate performance metrics
   - Generate visualizations

---

## 📊 Key Features

✅ **Multiple Transfer Learning Models** - Comparison of 8 different architectures  
✅ **Pre-trained Weights** - Leverages ImageNet pre-trained models  
✅ **Comprehensive Evaluation** - Accuracy, Precision, Recall, F1-Score metrics  
✅ **Data Visualization** - Training curves, confusion matrices, ROC curves  
✅ **Reproducible Results** - Well-documented code and methodology  

---

## 📈 Results & Performance

Each model notebook contains detailed performance metrics and visualizations comparing:
- Training and validation accuracy
- Loss curves
- Confusion matrices
- Classification reports
- ROC-AUC curves

---

## 📚 Dataset Information

- **Source:** Kaggle Chest CT Scan Images
- **Type:** Medical imaging dataset (CT scans)
- **Use Case:** Lung cancer detection and classification
- **Image Format:** JPG/PNG
- **Classes:** Binary or multi-class classification

---

## 🔧 Technologies Used

- **Deep Learning Frameworks:** TensorFlow, Keras
- **Computer Vision:** OpenCV
- **Data Processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Evaluation:** Scikit-learn

---

## 📝 How to Use This Project

1. **For Model Comparison:** Review the performance metrics in each notebook
2. **For Implementation:** Use individual notebooks as templates for your own projects
3. **For Research:** Reference the methodology and model configurations
4. **For Deployment:** Extract trained model weights from the notebooks

---

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Submit issues and bug reports
- Fork the repository and create pull requests
- Suggest improvements or new models
- Share your own results

---

## 📄 License

This project is licensed under the **Apache License 2.0** - see the LICENSE file for details.

---

## 👤 Author

**Nayon09**  
GitHub: [@Nayon09](https://github.com/Nayon09)

---

## 🔗 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Transfer Learning Techniques](https://en.wikipedia.org/wiki/Transfer_learning)

---

## ⭐ Acknowledgments

- Dataset provided by Kaggle community
- Transfer learning techniques from leading deep learning research
- Open-source community for tools and libraries

---

**Last Updated:** 2026-04-26