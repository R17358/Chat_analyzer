# WhatsApp Chat Analyzer

A Streamlit web application that allows users to upload WhatsApp chat exports and get detailed analytics of the conversations, including message stats, activity trends, word clouds, and more.

## 📌 Features

* Upload WhatsApp chat `.txt` files directly.
* Analyze chats by individual users or overall group stats.
* Get total message count, media shares, link shares, and word count.
* Visualize:

  * Monthly & daily message timeline.
  * Most active months and weekdays.
  * Most active users in the group.
  * Word cloud of most frequently used words.

## 🧠 Technologies Used

* Python 🐍
* Streamlit 📊
* pandas & matplotlib 📈
* WordCloud & URLExtract ☁️

## 📁 File Structure

```
├── app.py                # Main Streamlit app
├── functions.py          # Data analytics & visualization logic
├── preprocessor.py       # Chat data cleaning and preprocessing
├── README.md             # Project documentation
├── .github               # GitHub configs (if any)
```

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

> Make sure you have Streamlit and all required packages installed. If `requirements.txt` is not present, install manually:

```bash
pip install streamlit pandas matplotlib wordcloud urlextract
```

### 3. Start the App

```bash
streamlit run app.py
```

## 📤 Upload Instructions

1. Export a chat from WhatsApp (without media).
2. Upload the exported `.txt` file using the sidebar.
3. Select a user (or 'Overall') and click "Analyse".

## 📝 Screenshots

Add screenshots here to visually demonstrate your app (e.g. word cloud, message timeline, etc.)

## 💡 Future Improvements

* Emoji analysis and sentiment detection
* Filter by date ranges
* Export insights as reports
* Language detection

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Built with ❤️ using Streamlit by [Your Name](https://github.com/your-username)
