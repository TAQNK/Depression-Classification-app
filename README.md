# Depression-Classification-app
Help in classifying depression using user's text , facial and audio data .
This project focuses on detecting early-stage depression using a multi-modal deep learning approach.  
The system analyzes three different types of inputs:

- 📝 Text (using BERT)
- 😊 Facial Emotions (using CNN)
- 🎤 Audio Signals (using LSTM)
- ⚙️ Backend integration using Flask

By combining predictions from multiple modalities, the system improves reliability and detection accuracy for early signs of depression.

---

## 🚀 Features

- Text-based depression detection using BERT
- Facial emotion recognition using Convolutional Neural Networks (CNN)
- Audio-based emotion analysis using LSTM
- REST API built with Flask
- Modular and scalable architecture
- Cloud deployment ready

---

## 🧠 Models Used

### 1️⃣ Text Classification – BERT
- Pretrained BERT model fine-tuned for depression classification
- Context-aware language understanding
- Binary classification: Depressed / Not Depressed

### 2️⃣ Facial Emotion Recognition – CNN
- Convolutional Neural Network trained on facial emotion datasets
- Detects emotions such as:
  - Sad
  - Happy
  - Neutral
  - Angry
- Emotional patterns contribute to depression prediction

### 3️⃣ Audio Classification – LSTM
- Long Short-Term Memory (LSTM) network
- Uses extracted MFCC features from speech
- Captures sequential speech patterns related to depressive behavior

---

## 🏗️ System Architecture

User Input (Text / Image / Audio)  
        ↓  
Preprocessing  
        ↓  
Model Prediction (BERT / CNN / LSTM)  
        ↓  
Prediction Fusion Layer  
        ↓  
Flask Backend API  
        ↓  
Final Depression Classification  

---

## 🛠️ Tech Stack

- Python
- PyTorch / TensorFlow
- Hugging Face Transformers
- OpenCV
- Librosa
- Flask
- NumPy
- Pandas

---

## 📂 Project Structure

```
depression-classification/
│
├── models/
│   ├── bert_model/
│   ├── cnn_model/
│   ├── lstm_model/
│
├── static/
├── templates/
│
├── app.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/depression-classification.git
cd depression-classification
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
```

Activate Environment:

Windows:
```
venv\Scripts\activate
```

Linux / Mac:
```
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```
python app.py
```

Server will run at:

```
http://127.0.0.1:5000/
```

---

## 📊 Model Performance (Sample Results)

| Model | Accuracy |
|-------|----------|
| BERT (Text) | ~90% |
| CNN (Facial Emotion) | ~85% |
| LSTM (Audio) | ~82% |
| Combined Multi-Modal Model | ~92% |

---

## 🔐 Ethical Disclaimer

- This project is for research and educational purposes only.
- It is NOT a medical diagnostic tool.
- For clinical diagnosis, consult licensed mental health professionals.

---

## 🔮 Future Improvements

- Real-time video emotion analysis
- Attention mechanism for audio model
- Model quantization for mobile deployment
- Explainable AI integration
- Improved dataset balancing

---

## 🤝 Contribution

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Your Name  
GitHub: https://github.com/your-username
