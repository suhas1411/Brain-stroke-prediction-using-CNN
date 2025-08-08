### **CNN & Transfer Learning for Image Classification**

### **Overview**

This project demonstrates brain stroke CT scan image classification using **Convolutional Neural Networks (CNN)** and **Transfer Learning** with the **VGG16** architecture. It provides three distinct implementations, each applying different techniques to boost performance, accuracy, and efficiency.

---

### **Dataset**

Datasets sourced from Kaggle:

* [Brain Stroke Prediction CT Scan Image Dataset](https://www.kaggle.com/datasets/noshintasnia/brain-stroke-prediction-ct-scan-image-dataset)
* [Brain Stroke CT Scan Image](https://www.kaggle.com/datasets/alymaher/brain-stroke-ct-scan-image)

**Expected Directory Layout:**

```
Dataset/
 ├── Train/
 ├── Test/
 └── Validation/
```

---

### **Implementation Details**

#### **Model 1 – Basic CNN**

* Layers: `Conv2D`, `MaxPooling2D`, `Dense`, `Flatten`
* Activations: ReLU (hidden layers), Sigmoid (output)
* Optimizer: Adam
* Loss Function: Binary Crossentropy

#### **Model 2 – Transfer Learning with VGG16**

* Base Model: Pre-trained **VGG16** on ImageNet
* Added Layers: `Dense`, `Dropout`
* Optimizer: Adam (reduced learning rate)
* Loss Function: Binary Crossentropy

#### **Model 3 – Advanced CNN with Regularization**

* Extra Components: `BatchNormalization`, `Dropout`
* Layers: `Conv2D`, `MaxPooling2D`, `BatchNormalization`, `Dropout`, `Dense`, `Flatten`
* Optimizer: Adam
* Loss Function: Binary Crossentropy

---

### **How to Run**

1. Pick a script (Model 1, Model 2, or Model 3).
2. Each script will:

   * Load and preprocess datasets
   * Define and compile the network
   * Train with TensorBoard logging
   * Evaluate model performance on test data
   * Generate predictions and visual metrics

---

### **Visual Analysis**

* Training vs. validation accuracy/loss graphs
* Predicted outputs on test samples

---

### **Results**

* Final accuracy and loss metrics per model
* Side-by-side performance comparison through visualizations

---

### **License**
The Code 1 is licensed under the MIT License.
Link: https://opensource.org/licenses/MIT
Model 1 is distributed under the [MIT License](https://opensource.org/licenses/MIT).

---

If you want, I can now create **the same project structure** but rewritten for your **"Pavement Damage Classification with MobileNetV2"** so both projects look consistent in style. That way your documentation will have a uniform professional format.
