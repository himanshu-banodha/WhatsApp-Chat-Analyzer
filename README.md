# WhatsApp Chat Analyzer

Welcome to the WhatsApp Chat Analyzer! This web application allows you to upload and analyze your WhatsApp chat data to gain insights into your conversations. Built using Streamlit, this app provides an easy-to-use interface for exploring chat statistics and trends.

## Features
* **Upload WhatsApp Chat Files:** Upload your exported WhatsApp chat files (.txt format).
* **Message Analysis:** View the total number of messages, most active users, and other key statistics.
* **Daily Activity:** Analyze message frequency by day and time.
* **Word Cloud:** Visualize the most frequently used words in the chat.
* **Emoji Analysis:** See the most commonly used emojis.
* **Interactive Visualizations:** Explore your chat data through interactive charts and graphs.

## Demo
You can check out the live demo of the application [here](https://whatsapp-chat-analyzer-hb.streamlit.app/) - Refresh the page link if the content is not showing properly.

## Installation
To run this project locally, follow these steps:

**1. Clone the repository**
```
git clone https://github.com/himanshu-banodha/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```
**2. Install the required dependencies**
Make sure you have Python 3.7+ and pip installed. Then, run:
```
pip install -r requirements.txt
```
**3. Run the Streamlit app**
```
streamlit run app.py
```

## Usage
1. Open your web browser and go to http://localhost:8501.
2. Upload your WhatsApp chat file (in .txt format).
3. Explore the various statistics and visualizations generated by the app.

## Analysis Details

### Message Analysis
Get insights into the total number of messages, identify the most active users, and uncover other key statistics from your chat data.

### Daily Activity
Analyze the frequency of messages sent per day and identify peak activity times.

### Word Cloud
Visualize the most frequently used words in your chat conversations with an interactive word cloud.

### Emoji Analysis
See which emojis are used most often and understand the emotional tone of your conversations.

### Tools and Libraries Used
* **Streamlit:** For creating the web application.
* **Pandas:** For data manipulation and analysis.
* **Matplotlib:** For creating visualizations.
* **WordCloud:** For generating word clouds.
* **Emoji:** For handling and analyzing emoji data.
