# ✋ Real-Time Sign Language Detection

This project is my **university final year project**, aiming to bridge the communication gap for the deaf and hard-of-hearing community by translating sign language into readable text in **real time**. The system leverages **Python**, **OpenCV**, and **MediaPipe** to detect and interpret **alphanumeric hand gestures** accurately and efficiently.

---

## 🎯 Project Objective

To build a computer vision-based system that:
- Detects hand gestures via webcam
- Classifies them into alphanumeric signs (A-Z, 0-9)
- Displays the translated characters in real time
- Assists in communication for individuals with hearing/speech impairments

---

## 🛠️ Technologies Used

- 🐍 **Python** – Core programming language
- 🖼️ **OpenCV** – Real-time computer vision processing
- 🖐️ **MediaPipe** – Hand detection and tracking
- 🧠 **Custom ML Model** – For gesture classification (pickle + `.p` model)
- 📦 **NumPy, Pandas** – Dataset handling and analysis

---

## 📁 Project Structure

├── CollectImage.py # Capture hand gesture images for the dataset
├── CreateDataset.py # Preprocess and label captured data
├── TrainClassifier.py # Train the gesture classification model
├── InferenceClassifier.py # Real-time prediction using webcam
├── model.p # Trained classifier model
├── data.pickle # Label encoding and mappings
├── README.md # Project documentation



---

## 🚀 How It Works

1. **CollectImage.py**  
   - Use webcam to capture hand gestures (A-Z, 0-9)  
   - Save the images in structured folders for dataset creation

2. **CreateDataset.py**  
   - Preprocess image data  
   - Create a training-ready dataset for the ML model

3. **TrainClassifier.py**  
   - Use the dataset to train a classifier (e.g., KNN, SVM, etc.)  
   - Save the model for inference

4. **InferenceClassifier.py**  
   - Live webcam feed + MediaPipe hand tracking  
   - Predicts gesture and shows the result in real-time

---

## 💡 Key Features

- ⏱️ **Real-Time Prediction** with frame-by-frame classification
- 🧠 **Custom Model Training** for alphanumeric hand signs
- 🎥 **Live Webcam Support** with hand tracking
- 🌐 **Scalable** for future language/model extension (e.g., full ASL, BSL)

---

## 🧪 Example Use Case

> A deaf user signs the letter “A” using one hand before the camera.  
> The model detects hand keypoints using MediaPipe → Classifies the pose → Displays “A” on screen.

---

## 📸 Sample UI

> _(Insert screenshot or demo gif here)_  
> Example:  
> Real-time hand gesture detected → Result printed → Smooth and accurate UI experience

---

## 📌 Future Improvements

- 🔤 Support for full ASL (not just A-Z/0-9)
- 📱 Android App using MLKit + Flutter
- 🗣️ Voice conversion of recognized signs
- 🧩 Integrate with Google Translate API for multi-language support

---

## 🧑‍🎓 Developed By

**Nayem Hasan**  
Final Year Student, Computer Science & Engineering  
Dhaka City College  
[GitHub](https://github.com/NayemHasanLoLMan)

---

## 📜 License

This open-source project is available under the [MIT License](LICENSE).

