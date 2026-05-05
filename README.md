# Real-Time-Voice-Enabled-Review-Assistant-For-Amazon
A real-time voice-enabled Amazon review assistant is a simple and powerful tool that helps you make smart purchasing decisions without needing to read through countless reviews. By simply speaking, you can get instant summaries of product reviews, ask specific questions about a product, and receive audio responses. 
Real-Time Voice-Enabled Review Assistant
📌 Detailed List of Software and Dependencies
1️⃣ Python (The Engine)
•	Purpose: The core programming language used for the entire backend logic, scraping, and AI integration.
•	Download: python.org/downloads
•	Installation: Ensure you check "Add Python to PATH" during setup.
2️⃣ Streamlit (The Interface)
•	Purpose: A powerful framework to build the web-based dashboard and interactive UI without needing complex HTML/CSS.
•	Installation: pip install streamlit
3️⃣ Google Generative AI (The Brain)
•	Purpose: Connects your app to the Gemini 1.5 Flash model for summarizing reviews and answering user queries.
•	Installation: pip install google-generativeai
4️⃣ SpeechRecognition (The Ears)
•	Purpose: Captures your voice through the microphone and converts it into text so the AI can understand your questions.
•	Installation: pip install SpeechRecognition
•	Note: You may also need to install PyAudio (pip install pyaudio).
5️⃣ gTTS & pyttsx3 (The Voice)
•	Purpose: Converts the AI's text responses back into spoken audio. gTTS provides a natural Google voice, while pyttsx3 can work offline.
•	Installation: pip install gTTS pyttsx3
6️⃣ BeautifulSoup4 & Requests (The Scrapers)
•	Purpose: Requests fetches the Amazon webpage, and BeautifulSoup parses the HTML to extract prices, ratings, and features.
•	Installation: pip install beautifulsoup4 requests
7️⃣ Altair & Pandas (The Analytics)
•	Purpose: Pandas handles the product data in tables, and Altair creates the interactive bar charts for star ratings.
•	Installation: pip install altair pandas
8️⃣ Dotenv (The Security)
•	Purpose: Loads your Gemini API Key securely from a .env file so it isn't hardcoded in your script.
•	Installation: pip install python-dotenv

Hardware & Environment Requirements
Component	Requirement
Microphone	Required for the "Tap to Speak" Q&A feature.
Internet	Required for Web Scraping and Gemini API calls.
API Key	A valid Google AI Studio key (free tier is sufficient).
Browser	Chrome, Edge, or Firefox (version 109+).

