# *🖼 Fake Image Detection*  

## *📌 Overview*  
This project classifies images as *real or fake* using a *Convolutional Neural Network (CNN). The model detects **AI-generated, deepfake, or manipulated images. Implemented with **Python, TensorFlow, Keras, and OpenCV, it runs on **Google Colab*.

---

## *📂 Dataset*  
✅ *Real Images* – Authentic, unaltered images.  
✅ *Fake Images* – AI-generated or manipulated images.  

Images are preprocessed and normalized for better performance.

---

## *📌 Model Architecture*  
✔ *3 Convolutional Layers* with ReLU activation  
✔ *Batch Normalization & MaxPooling*  
✔ *Flatten & Dense Layers* with Dropout  
✔ *Sigmoid Activation* for binary classification  

The model outputs *0 (Real) or 1 (Fake)*.

---

## *📊 Training & Evaluation*  
✅ *Binary Crossentropy Loss*  
✅ *Adam Optimizer*  
✅ *Augmented Data*  
✅ *Early Stopping* to prevent overfitting  

---

## *🖥 Run on Google Colab*  
Try the model in *Google Colab, created by **MOHIT SAI BALAJI*.  


---

## *📌 How to Use*  
1️⃣ Upload an image to Colab.  
2️⃣ The model predicts whether it’s *Real* or *Fake*.  
3️⃣ Displays the image with the prediction label.

---

## *🚀 Technologies Used*  
✔ *Python*  
✔ *TensorFlow / Keras*  
✔ *OpenCV*  
✔ *NumPy & Pandas*  
✔ *Matplotlib*  

---

## *📌 Run Locally*  
bash
git clone https://github.com/Mohitsaibalaji/Fake-Image-Detection.git
cd Fake-Image-Detection
pip install -r requirements.txt
python predict.py --image test.jpg


---

## *🔗 Credits*  
🔹 *Author:* MOHIT SAI BALAJI  
🔹 *GitHub Repository:* [Fake Image Detection](https://github.com//Fake-Image-Detection)  

---
