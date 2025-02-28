# WhatsApp-Chat-Analyzer-Project

🔍 Project Overview:

The WhatsApp Chat Analyzer is a Machine Learning-based data analysis tool that extracts meaningful insights from WhatsApp chat data. Using Natural Language Processing (NLP) techniques and data visualization, the tool helps users analyze chat activity, most common words, emoji usage, busiest users, and more.

This project is built using Python, Streamlit, Pandas, Matplotlib, Seaborn, and WordCloud. It enables users to upload WhatsApp chat files and visualize detailed analytics on chat conversations.



✨ Features:

✅ 1. Upload & Preprocess WhatsApp Chat Data
Supports WhatsApp chat files (.txt) exported from group or private chats.
Extracts timestamps, usernames, and messages from the chat.
Filters out system messages (e.g., "User left the group").
Removes media messages (<Media omitted>) from analysis.

✅ 2. Generate Chat Statistics
📩 Total Messages - Counts the total number of messages exchanged.
📝 Total Words - Calculates the total words sent in the chat.
🖼️ Media Shared - Tracks the number of images, videos, and documents sent.
🔗 Links Shared - Extracts and counts URLs shared in the conversation.

✅ 3. Analyze Chat Activity Over Time
📅 Monthly Timeline - Shows how the chat activity changed over time.
📆 Daily Timeline - Highlights the most active days.
📊 Weekly Heatmap - Displays chat activity trends by day and hour.

✅ 4. Identify the Most Active Users
🏆 Busiest Users - Ranks users by the number of messages sent.
📊 User Contribution Percentage - Shows the % of messages sent by each user.

✅ 5. Word Cloud Generation
☁️ Word Cloud Visualization - Displays the most frequently used words.
❌ Stopword Removal - Filters out common stopwords (e.g., "the", "is", "are").

✅ 6. Most Common Words Analysis
Displays Top 20 most frequently used words.
Excludes irrelevant words and stopwords.

✅ 7. Emoji Analysis
😃 Detects and counts emojis used in the chat.
📊 Pie chart visualization of the most frequently used emojis.



🎯 Future Improvements:

🚀 Sentiment Analysis - Detect positive/negative messages in chat.
📌 Chatbot Integration - Use AI to summarize chat conversations.
📊 Advanced NLP Techniques - Implement Topic Modeling & Named Entity Recognition.
📂 Database Storage - Store chat analysis history for long-term tracking.
