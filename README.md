🎵 Emotion-Based Music Recommendation System
An AI-powered system that detects human emotions in real-time from images and recommends Bollywood and Hollywood songs tailored to the detected emotion using NLP techniques.

🚀 Project Highlights
🖼️ Real-Time Emotion Detection
Detects emotions from live webcam feed or uploaded images using a pretrained CNN-based model (e.g., ResNet50 backbone with a custom classifier) with ~90% accuracy.


🎶 Music Recommendation Based on Emotion
Uses NLP techniques to map detected emotions to curated Bollywood and Hollywood song playlists, providing personalized music suggestions.


💬 Simple, Intuitive Interface
Users can upload images or use webcam for emotion detection and instantly receive song recommendations.


🧰 Technologies Used
Component	Framework / Library
Emotion Detection	TensorFlow/Keras (CNN-based model)
NLP for Recommendation	NLTK, Python dictionaries / rule-based matching
Dataset Management	Pandas, NumPy
Web Interface	Streamlit / Gradio (optional)


📦 Dataset Summary
Emotion-labeled image datasets (e.g., FER2013) for training/testing the emotion classifier

Curated Bollywood and Hollywood song lists categorized by emotions (happy, sad, angry, calm, etc.)


🧠 Model Architecture
Pretrained CNN backbone (e.g., ResNet50) for feature extraction

Custom dense classification head trained to detect emotions like Happy, Sad, Angry, Surprise, Neutral, etc.


Model achieves ~90% accuracy on standard emotion datasets

🎵 How It Works
Input: User uploads an image or uses webcam capture

Emotion Detection: Model predicts the emotion from the face

Recommendation: NLP module maps emotion label to corresponding Bollywood and Hollywood song lists

Output: Display or play recommended songs based on detected emotion

📂 Folder Structure (Example)
plaintext
Copy
Edit

📍 How to Run
🔧 Installation
bash
Copy
Edit
git https://github.com/Muhammad-junaid-mujtaba/music-recomenation-by-emotions.git
cd emotion-music-recommender
pip install -r requirements.txt
🖼️ Run the App (Streamlit Example)
bash
Copy
Edit

streamlit run app/main.py

📬 Contact
Author: Junaid
Email: junaidqazi705@gmail.com
