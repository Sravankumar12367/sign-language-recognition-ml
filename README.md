# 🤟 Sign Language Recognition using Machine Learning

A real-time hand gesture recognition system developed as a college group project. This application detects sign language gestures using a webcam and translates them into readable text using computer vision and machine learning.

---

## 👥 Team Project

This project was developed by a team of 4 members as part of a college major project.

**Team Members:**

* Sravankumar
* Amar
* Chandrahas
* Shiva

---

## 🚀 Features

* 📷 Real-time hand detection using webcam
* ✋ Hand tracking using CVZone (MediaPipe)
* 🧠 Gesture classification using trained ML model
* 🔤 Converts hand signs into text output
* ⚡ Fast and interactive prediction
* 📊 Dataset collection support

---

## 🛠️ Tech Stack

* **Python**
* **OpenCV**
* **CVZone**
* **NumPy**
* **Machine Learning (Keras Model)**

---

## 📂 Project Structure

```
sign-language-recognition/
│── datacollection.py
│── test.py
│── keras_model.h5
│── labels.txt
│── Data/
```

---

## ⚙️ How It Works

1. **Data Collection**

   * Captures hand gesture images using webcam
   * Images are resized and preprocessed

2. **Model Prediction**

   * Processed images are passed into trained model
   * Model predicts corresponding sign

3. **Output Display**

   * Predicted label is shown in real-time

---

## 🎯 My Contribution

* Implemented hand detection and image preprocessing
* Worked on real-time prediction logic
* Integrated OpenCV and CVZone modules
* Assisted in testing and debugging

*(Edit this based on your actual contribution)*

---

## ▶️ How to Run

```bash
pip install opencv-python cvzone numpy
python test.py
```

---

## 📌 Supported Signs

Includes gestures like:
Hello, Yes, No, Thank You, Please, Eat, Drink, and more.

---

## 🚀 Future Improvements

* Add more gesture classes
* Improve model accuracy
* Convert output to speech
* Build GUI / web app

---

## 👨‍💻 Author

**Sravankumar (Team Member)**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
