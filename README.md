# Sign-Language

### 📄 `README.md`


# 🧠 Sign Language Detection and Representation System

This project is a real-time sign language recognition system that detects hand gestures via webcam and represents them as corresponding text. Built using Python, Flask, OpenCV, MediaPipe, and TensorFlow, the system helps bridge communication gaps for the hearing-impaired community.

## 🚀 Features

- ✋ Real-time hand gesture detection using webcam
- 🧠 Machine Learning model for sign classification
- 🎯 Custom dataset creation using Python scripts
- 📷 Uses MediaPipe and OpenCV for hand tracking
- 🌐 Web-based interface powered by Flask
- 🖼️ Sign representation through text/image

---

## 🛠️ Technologies Used

| Technology     | Purpose                         |
|----------------|----------------------------------|
| Python         | Core programming language       |
| Flask          | Web framework for backend        |
| OpenCV         | Image capturing and processing   |
| MediaPipe      | Hand landmark detection          |
| TensorFlow     | Training and prediction model    |
| HTML/CSS       | Frontend interface               |

---

## 📦 Project Structure

```

sign-language-project/
│
├── app.py                      # Flask server
├── static/
│   └── css/
│   └── └── home.css
│   └── js/
│   └── └── signin.js
│   └── signs/
│   └── └── 0.jpg
|   └── └── 1.jpg              
├── templates/
├── └── images/
│   └── └── signdetect.jpg
│   └── home.html              # Frontend page
│   └── login.html
│   └── sign_detection.html
│   └── sign_representation.html
│   └── sign_up.html   
├── create_dataset.py          # Script to create dataset
├── collect_images.py
├── inference_classifier.py
├── model.p
├── train_classifier.py        # Saved ML model
└── README.md                   # Project documentation

````

---

## 📷 Dataset Creation

- Run `create_dataset.py` to collect gesture images.
- The script captures frames from the webcam and saves them labeled by gesture name.
- Ensure good lighting and background while collecting data.

```bash
python create_dataset.py
````

---

## 🧠 Model Training

* Use `model_training.py` to train a CNN model using TensorFlow on the collected dataset.

```bash
python train_classifier.py
```

---

## 🌐 Running the Flask App

1. Start the Flask server:

   ```bash
   python app.py
   ```

2. Open your browser and go to `http://127.0.0.1:5000/`

3. Start showing hand gestures in front of your webcam.

---

## 📊 Future Improvements

* Add support for more gestures and complete words
* Integrate text-to-speech (TTS) for audio output
* Train model with ASL or ISL official datasets
* Add sign-to-sign communication for two-way interaction

---

## 🤝 Contributing

Pull requests and contributions are welcome! If you have suggestions or improvements, feel free to fork the repo and open a PR.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author


Email: \[[sravanapavanipucha@gmail.com](mailto:your.email@example.com)]
GitHub: \[https://github.com/Mounika9929/Sign-Language]

---
