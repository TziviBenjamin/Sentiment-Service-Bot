# Project: Interactive Service Bot powered by Gemini API

## Project Description
This system is a final project implementing the use of Large Language Models (Gemini API). The bot conducts an interactive conversation with the user in a selected service domain, while maintaining context and conversation history. The system includes emotional sentiment analysis performed at the end of the conversation, data storage in JSON format, and visualization of service quality insights using the Matplotlib library.

## Technical Requirements Implemented
* **Class Management:** Implementation of the `ServiceManager` class, which centralizes logic, communication with the API, and data management.
* **Communication:** Use of the Google Gemini API for intelligent dialogue management.
* **Data Processing:**
    * Use of `List of Dictionaries` to store conversation history.
    * Use of `List/Dictionary Comprehensions` for efficiency and text analysis.
    * Use of `Iterator/Generator` to traverse the conversation history.
    * Development of the `calculate_sentiment` function for text analysis based on a custom dictionary (Normalization, punctuation cleaning).
* **Storage:** Saving and loading JSON files containing conversation details.
* **Error Handling:** Implementing `try-except` mechanisms to handle communication faults and file read/write errors.
* **Visualization:** Generating graphs to display sentiment trends and compare tones between the user and the bot.

## System Architecture
1. **ServiceManager:** The main class for managing the bot's lifecycle.
2. **API Handler:** Functions for communication with the model.
3. **Data Persistence:** JSON file management.
4. **Analytics:** Sentiment analysis and graphical data presentation.

## Usage Instructions
1. Configure your API key in Google AI Studio.
2. Run the Notebook in a Jupyter environment.
3. Initialize the `ServiceManager` class and start the conversation.
4. Upon completion, use the load and analysis functions to view graphs and the conversation summary.

## Prerequisites
* Python 3.x
* Libraries: `google-generativeai`, `matplotlib`, `json`, `re`.

---
*Note: This file is intended to serve as technical documentation for the final project.*
