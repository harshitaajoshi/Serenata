# Serenata 🎶  

Serenata is a facial emotion-based song recommendation system that enhances music discovery by analyzing user emotions from an image and suggesting songs that match the mood. It integrates DeepFace for emotion detection, Gemini API for generating recommendations, and Spotify API to personalize suggestions based on listening history.  

## 📌 Project Overview  

This project was developed as part of a hackathon to explore how AI can enhance music experiences. By leveraging facial emotion analysis, Serenata tailors song recommendations in a unique and engaging way.  

## ⚙️ Requirements  

Ensure you have the following installed:  
- Python 3.9 or higher  
- `deepface` for facial emotion detection  
- `google-generativeai` for AI-generated song recommendations  
- `requests` for API interactions  
- `tensorflow` (only if TensorFlow-related operations are used)  
- `base64` (built-in, no installation needed)  
- `datetime` (built-in, no installation needed)  
- `httplib2` (install with `pip install httplib2` if necessary)  

## 🚀 Installation  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/yourusername/serenata.git
   cd serenata
   ```  
2. **Set up a virtual environment:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```  
3. **Install dependencies:**  
   ```bash
   pip install deepface google-generativeai requests tensorflow
   ```  
4. **Configure API keys:**  
   - **Spotify API:** Replace `client_id` and `client_secret` with your credentials.  
   - **Gemini API:** Set `API_KEY` to your Google Gemini API key.  

## 🎭 How It Works  

1. **Image Input:** Place an image (default: `abc.png`) in the project folder or update `img_path` in the script.  
2. **Run the script:**  
   ```bash
   python cutie.py
   ```  
3. **What Happens Next?**  
   - The system analyzes the image to detect dominant facial emotions.  
   - Based on the emotion, the Gemini API suggests a relevant song.  
   - If linked to Spotify, it enhances recommendations with listening history.  
   - The song recommendation, along with a Spotify link, is displayed.  

## 🔍 Key Features  

- **Facial Emotion Analysis:** Uses DeepFace to detect emotions.  
- **AI-Powered Music Suggestions:** Gemini API provides tailored song recommendations.  
- **Spotify Integration:** Fetches user listening history for personalized results.  

## ❗ Troubleshooting  

- Double-check API keys and credentials.  
- Ensure all dependencies are installed.  
- Verify the image file path and name.  
- If errors occur, refer to the documentation of the respective libraries.  

## 📜 License  

This project is open-source and available under the MIT License. See the `LICENSE` file for details.  
