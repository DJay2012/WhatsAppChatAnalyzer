# WhatsApp Chat Analyzer

This Streamlit app provides a comprehensive analysis of your WhatsApp chat logs, offering insights into messaging patterns, user activity, and overall communication trends. It visualizes various statistics, including message frequency, emoji usage, common words, monthly and daily activity, and more.  This allows you to understand your chat dynamics in a fun and informative way.

## Table of Contents

* [Features](#features)
* [How to Use](#how-to-use)
* [Requirements](#requirements)
* [Installation](#installation)
* [Running the App](#running-the-app)
* [Example Visualizations](#example-visualizations)
* [Troubleshooting](#troubleshooting)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)


## Features

* **Chat Statistics:** Displays key metrics like total messages, words, media shared, links shared, and deleted messages for the selected user or the entire group.
* **User-Specific Analysis:** Analyze chats for a specific participant or the entire group. This allows for individual contribution analysis in group chats.
* **Messaging Frequency:** Visualizes the percentage and count of messages sent by each user in a group chat.
* **Emoji Analysis:** Identifies and displays the most frequently used emojis, providing insights into emotional expression in the chat.
* **Common Words:** Extracts and displays the most frequent words used in the conversation, highlighting recurring themes and topics.
* **Monthly Timeline:** Shows the trend of message frequency over time, revealing periods of high and low activity.
* **Daily Timeline:** Visualizes message activity throughout the day, identifying peak hours and quiet periods.
* **Busy Days/Months:** Highlights the most active days of the week and months of the year, providing a calendar view of chat intensity.
* **Word Cloud:** Generates a word cloud to visually represent the most prominent words, giving a quick overview of the conversation's content.
* **Weekly Activity Heatmap:** Displays a heatmap of chat activity, showing the distribution of messages across days of the week and hours of the day.
* **Date Format Selection:** Allows users to specify the date format used in their chat log (dd-mm-yy or mm-dd-yy), ensuring accurate parsing.
* **Data Privacy:** The analysis is performed locally on your machine. Your chat data is not uploaded to any external server.

## How to Use

1. **Export Chat File:** Export your WhatsApp chat history from the app's settings. Choose the "Export chat" option and select "Without media" for faster processing. Exporting with media can significantly increase processing time.
2. **Upload Chat File:** In the app, click the "Choose a file" button and select the exported chat file (usually a `.txt` file).
3. **Select Date Format:** Choose the correct date format used in your chat log. This is crucial for accurate data parsing.
4. **Select User (Optional):** If you wish to analyze a specific user's activity, select their name from the sidebar dropdown. Choose "Everyone" to analyze the entire group chat.
5. **Show Analysis:** Click the "Show Analysis" button to generate the visualizations and statistics.

## Requirements

* Python 3.7 or higher
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud

## Installation

1. **Clone the Repository (or download the zip):**
   ```bash
   git clone 
   cd WhatsappChatAnalyzer