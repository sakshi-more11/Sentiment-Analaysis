# 🧠Sentiment-Analaysis
---
This is a simple Sentiment Analysis GUI Chatbot built using Python, Tkinter for GUI, and TextBlob for natural language processing. The chatbot analyzes the emotional tone (positive, negative, or neutral) of user-entered text and provides detailed polarity and subjectivity scores.

📌 Features:<br>

🔤 GUI-based input using Tkinter.<br>
😊 Detects Positive, 😐 Neutral, or 😞 Negative sentiment.<br>
📊 Displays polarity and subjectivity scores.<br>
🧠 Uses TextBlob and NLTK libraries.<br>
🔁 Reset functionality to clear the interface.<br>
✨ Fade-in effect to improve UX.<br>


🛠️ Installation:<br>

1️⃣Clone the repository:<br>
git clone https://github.com/your-username/your-repo-name.git<br>
cd your-repo-name<br>
2️⃣Install required libraries:<br>
pip install textblob nltk<br>
3️⃣Download NLTK data (the script handles this, but for safety):<br>
python<br>
import nltk<br>
nltk.download('punkt')<br>
4️⃣🚀Run the Application<br>
app.py<br>

💡 How it Works:-<br>

🔹The user enters a sentence.<br>
🔹TextBlob processes the sentence and returns:<br>
🔹Polarity: value from -1.0 (negative) to +1.0 (positive)<br>
🔹Subjectivity: value from 0.0 (objective) to 1.0 (subjective)<br>
🔹Based on polarity:<br>
   > 0: Positive<br>
   < 0: Negative<br>
   == 0: Neutral<br>
   The result is shown in the text box with an explanation.<br>
