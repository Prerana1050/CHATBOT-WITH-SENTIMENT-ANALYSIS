# CHATBOT-WITH-SENTIMENT-ANALYSIS
A Python-based chatbot that interacts with users and performs sentiment analysis. It stores the full conversation, displays sentiment for each user message (positive/negative/neutral), and provides a final overall emotional summary along with mood trend at the end of the chat.
You can Use This Directly
# Sentiment-Based Chatbot

## 🚀 How to Run
1. Install required library  


pip install textblob
python -m textblob.download_corpora

2. Run script  


python app.py


## 🛠 Technologies Used
- Python
- TextBlob (NLP Sentiment Analysis)

## 🧠 Sentiment Logic
- Polarity score from -1 to +1
- `> +0.1` → Positive
- `< -0.1` → Negative
- Between → Neutral

Each user message:
1. Sentiment is detected
2. Chatbot responds based on tone
3. Log is maintained to compute final sentiment

### Example Format
User: "Your service disappoints me"  
→ Sentiment: Negative  
Chatbot: "I'm sorry you feel that way. I'll improve!"

Final Output:  
Negative – general dissatisfaction

## 📌 Tier-2 Status (Completed)
✔ Conversation-level sentiment  
✔ Chatbot replies based on sentiment  
✔ Final summary after exit  
✔ Tests provided  
⭐ Bonus Features Included:
- Emoji-based emotional responses 😄😞
- Multiple inputs considered for final result

## Folder Structure


📂 sentiment-chatbot
│── app.py
│── README.md
│── test_app.py (optional)
