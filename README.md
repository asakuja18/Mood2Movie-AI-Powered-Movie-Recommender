# Mood2Movie-AI-Powered-Movie-Recommender

Mood2Movie is an AI-powered movie recommendation system that detects a user's emotional state from natural language text and recommends movies that match their mood. The system combines modern NLP techniques with intelligent recommendation logic to deliver a personalized entertainment experience.

## 🎯 Key Skills Demonstrated

- Natural Language Processing (NLP)
- Transformer Models (DistilBERT)
- Machine Learning
- Recommendation Systems
- Streamlit Application Development
- API Integration
- Python Development

---

## 📌 Problem Statement

Traditional movie recommendation systems rely heavily on viewing history, ratings, and user preferences. However, they often fail to consider a user's current emotional state.

Mood2Movie addresses this challenge by analyzing user-written mood descriptions and recommending movies that align with their emotions in real time.

---

## 🚀 Features

- Emotion detection from natural language text
- DistilBERT-based mood classification
- TF-IDF + SVM baseline model comparison
- Mood-based movie recommendations
- Movie similarity recommendations
- TMDb poster integration
- Interactive Streamlit web application
- Real-time recommendation generation

---

## 🧠 AI Models Used

### 1. DistilBERT (Primary Model)
- Fine-tuned Transformer-based classifier
- Detects emotions from user text
- Provides contextual understanding of language
- Handles nuanced emotional expressions

### 2. TF-IDF + SVM (Baseline Model)
- Traditional NLP pipeline
- Lightweight and interpretable
- Used for benchmarking and comparison

---

## 😊 Supported Emotions

The system classifies user input into five emotional categories:

- Happy
- Sad
- Chill
- Thrilling
- Dark

---

## 🎥 Recommendation Methods

### Mood-Based Recommendation
Users enter a sentence describing how they feel.

Example:

"I feel exhausted and need something relaxing."

The model predicts the emotion and recommends movies associated with that mood.

### Movie Similarity Recommendation

Users can also search for a movie title and receive similar movie recommendations using cosine similarity and TF-IDF vector representations.

---

## 📊 Dataset

### Emotion Dataset
- 1,000 labelled mood phrases
- 5 emotion categories
- Custom-created dataset

### Movie Dataset
- TMDb 10,000 Movie Dataset
- Movie titles
- Genres
- Plot summaries
- TMDb IDs

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Hugging Face Transformers
- DistilBERT
- Scikit-Learn
- TF-IDF
- Support Vector Machine (SVM)
- Pandas
- NumPy
- Pickle
- TMDb API

---

## 🏗️ System Workflow

1. User enters mood text
2. DistilBERT predicts emotion
3. Mood category is identified
4. Relevant movies are retrieved
5. Movie posters are fetched from the TMDb API
6. Recommendations are displayed through Streamlit



---

## 📸 Application Screenshots

### Main Interface

<img width="465" height="475" alt="image" src="https://github.com/user-attachments/assets/ae9b2a83-666f-4a56-bd9d-5b39685aeeba" />

The Streamlit homepage where users can choose mood-based or movie-based recommendations.

---

### Mood-Based Recommendation Example

<img width="422" height="545" alt="image" src="https://github.com/user-attachments/assets/af6ef900-c456-44a0-9b13-c4251d08e071" />


Example showing emotion detection from user text and mood-based movie recommendations.

---

### Movie Similarity Recommendation

<img width="433" height="556" alt="image" src="https://github.com/user-attachments/assets/f43b0857-59e9-4e2d-b8dc-06e3e7a248b9" />


Example showing movie recommendations generated from a selected movie title.

---

## 📈 Results

The system successfully detects emotions from user text and generates personalized movie recommendations.

Models Evaluated:
- DistilBERT
- TF-IDF + SVM

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Mood2Movie.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run MRS_MAIN_TEXT_MODE.py
```

---

## 🔮 Future Improvements

- Multilingual emotion detection
- Voice-based mood analysis
- Mobile application deployment
- Integration with streaming platforms
- Multimodal emotion recognition using text, voice, and images

-- Due to GitHub size limitations, the complete project (including trained models and datasets) is hosted externally:

👉 [Download Full Project from Google Drive] (https://drive.google.com/drive/folders/1Ap-3Zeobrfm2dW-lz7pVMlBLKaYYYn7d?usp=drive_link)

---

## 📌 Note
This repository contains only the source code and essential files required to understand and run the project.


## 👨‍💻 Author

**Ankit Sakuja**


