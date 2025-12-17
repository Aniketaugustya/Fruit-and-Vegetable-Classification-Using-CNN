# Fruit-and-Vegetable-Classification-Using-CNN
CNN-based image classification project for recognizing fruits and vegetables using TensorFlow/Keras. Focused on understanding data preprocessing, CNN architecture, and model training through a hands-on Jupyter Notebook.
# Fruit & Vegetable Image Classification using CNN

This repository contains a **Convolutional Neural Network (CNN)** implementation for classifying fruit and vegetable images using **TensorFlow/Keras**. The core work is documented in a Jupyter Notebook (`.ipynb`) intended for learning, experimentation, and baseline model development.

If you’re expecting production-grade ML here, stop. This is a **clear, educational baseline**, not a deployment-ready system.

---

## 📌 Project Overview

* **Task**: Multi-class image classification (fruits & vegetables)
* **Approach**: Supervised learning with CNN
* **Framework**: TensorFlow + Keras
* **Dataset**: Fruit and Vegetable Image Recognition dataset (commonly used on Kaggle)
* **Goal**: Learn CNN fundamentals — not chase SOTA accuracy

---

## 🧠 What This Notebook Covers

* Dataset loading using `ImageDataGenerator`
* Image preprocessing and augmentation
* CNN architecture design
* Model compilation and training
* Validation performance monitoring
* Basic evaluation and observations

No AutoML. No shortcuts. You actually see what’s happening.

---

## 🗂 Repository Structure

```
├── cnn-fruit-vegetable-cognition.ipynb   # Main Jupyter Notebook
├── README.md                            # Project documentation
```

Simple on purpose.

---

## ⚙️ Requirements

Make sure you have the following installed:

* Python 3.8+
* TensorFlow 2.x
* NumPy
* Matplotlib
* Jupyter Notebook

Install dependencies quickly:

```bash
pip install tensorflow numpy matplotlib jupyter
```

---

## 📊 Dataset Setup

This notebook assumes a directory structure like:

```
dataset/
├── train/
│   ├── apple/
│   ├── banana/
│   └── ...
├── validation/
│   ├── apple/
│   ├── banana/
│   └── ...
```

If your dataset structure is different, the code **will break**. Fix the paths instead of blaming the model.

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the notebook:

   ```bash
   jupyter notebook cnn-fruit-vegetable-cognition.ipynb
   ```

3. Update dataset paths if required

4. Run cells sequentially — don’t skip and then wonder why it fails

---

## 📈 Results

* Accuracy depends heavily on dataset quality and class balance
* Overfitting is possible (and likely) if augmentation is weak
* This model is a **starting point**, not a final solution

If your accuracy is bad, that’s not shocking. Learn *why* instead of tweaking random layers.

---

## 🚧 Limitations (Read This)

* No hyperparameter optimization
* No test-set evaluation
* No model saving/loading pipeline
* No deployment or inference API

All of these are **your responsibility** if you want to go further.

---

## 🔮 Possible Improvements

* Add Dropout & Batch Normalization properly
* Use Transfer Learning (MobileNetV2, ResNet)
* Add confusion matrix & classification report
* Export trained model (`.h5` or `.keras`)
* Build a simple inference script

Until you do these, don’t call this “complete”.

---

## 🧑‍💻 Author

Developed by **Augustya**
(Student • Engineer • Learning ML the hard way)

---

## 📜 License

This project is open for educational use. If you copy it blindly, you’re only cheating yourself.
