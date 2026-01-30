# 👕 Fashion-MNIST Image Classification

---

## 📌 Google Colab
🔗 [Open in Google Colab](https://colab.research.google.com/drive/1wxvAfFBj4bnWxjskCEtUfC1L9T3lRAA6?usp=drive_link)

---

## Questions

### 1️⃣ What is the Fashion MNIST dataset?
The Fashion MNIST dataset is a collection of 70,000 grayscale images of clothing items such as shirts, shoes, bags, and trousers. Each image is 28×28 pixels and belongs to one of 10 clothing categories. It is commonly used to train and test image classification models in machine learning.

---

### 2️⃣ Why do we normalize image pixel values before training?
We normalize image pixel values to scale them between 0 and 1 instead of 0 to 255. This helps the model learn faster, improves numerical stability, and allows the neural network to converge more efficiently during training.

---

### 3️⃣ Layers used in the neural network

**Flatten Layer**  
→ Converts the 2D image (28×28) into a 1D array.

**Dense (128 neurons, ReLU)**  
→ Learns patterns and important features from the images.

**Dense (10 neurons)**  
→ Output layer representing the 10 clothing classes.

---

### 4️⃣ What is an epoch?
An epoch means one complete pass of the entire training dataset through the neural network.

---

### 5️⃣ Prediction vs Actual Label
- **Predicted label**: Model output  
- **Actual label**: True dataset label  

✔ Same = correct  
✖ Different = incorrect

---

### 6️⃣ How to improve accuracy
- Increase epochs  
- Add more layers  
- Use Dropout  
- Apply data augmentation  
- Tune hyperparameters
