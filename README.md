# Image-based-breed-recognition-for-bovine-of-India
AI based breed recognition for cattle and buffaloes of India

# 🐄 Image-Based Breed Recognition for Cattle & Buffaloes (SIH25004)

## 📌 Background
The Bharat Pashudhan App (BPA) records animal breeding, health, and nutrition data.  
A major challenge is **incorrect breed identification** by field workers, which reduces data quality.

## 🚀 Solution
We propose an **AI-based system** that:
- Identifies cattle & buffalo breeds from images
- Works in different lighting and poses
- Suggests/validates breed during BPA registration
- Provides a simple UI for field workers

## 🛠 Tech Stack
- Python
- TensorFlow / PyTorch
- OpenCV
- Streamlit
- scikit-learn

## ⚙️ Setup
```bash
git clone https://github.com/<your-username>/cattle-breed-recognition.git
cd cattle-breed-recognition
pip install -r requirements.txt
streamlit run app.py
