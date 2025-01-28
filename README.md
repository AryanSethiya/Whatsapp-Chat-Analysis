# 📊 WhatsApp Chat Analysis  

## Overview  
This is a **Streamlit** application that helps analyze your WhatsApp chats. It provides insights such as message frequency, most active users, word cloud visualization, and sentiment analysis.  

🚀 **Live Demo:** [Click Here](https://wca-campusx.herokuapp.com/)  

## Features  
- 📈 **Message Frequency Analysis**  
- 🏆 **Most Active Users**  
- ☁️ **Word Cloud Generation**  
- 📊 **Emoji & Media Insights**  
- 📅 **Activity Trends (Hourly, Daily, Monthly)**  
- 🔍 **Sentiment Analysis (Optional)**  

## File Structure  
- `app.py` - Main application script  
- `helper.py` - Contains utility functions  
- `preprocessor.py` - Handles chat data preprocessing  
- `requirements.txt` - Dependencies for the project  
- `setup.sh` - Deployment script  
- `stop_hinglish.txt` - Stopwords for text analysis  
- `Procfile` - Configuration for Heroku deployment  

## Installation  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/your-repo-name/whatsapp-chat-analysis.git
cd whatsapp-chat-analysis
pip install -r requirements.txt
```
## Usage  
Run the Streamlit app locally:  
```bash
streamlit run app.py
```
## Deployment
Deploy easily on Heroku using:

```bash
heroku create your-app-name
git push heroku main
```
## Future Enhancements
📊 Add more detailed sentiment analysis
🏷️ Implement topic modeling
📌 Improve visualization options
