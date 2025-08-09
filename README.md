# Vidsnap-AI
🎥 VidSnap AI
An AI-powered video downloader and summarizer built with Python, Streamlit, and the OpenAI API. This project allows users to fetch videos from YouTube, process them into text, and generate AI-powered summaries, insights, and highlights.

🚀 Features

📥 Video Downloader – Download videos directly from YouTube by providing the link.

📝 AI Summarizer – Summarize the content of the video using OpenAI's GPT model.

🔍 Key Insights – Extract the most important points from the video.

💬 Transcript Generation – Convert video speech into readable text.

🌐 Web Interface – Easy-to-use UI powered by Streamlit.

🛠️ Tech Stack

Frontend & UI: Streamlit

Backend: Python

APIs: OpenAI API

Video Processing: pytube, moviepy

Speech-to-Text: Whisper API / OpenAI transcription

📦 Installation & Setup
1️⃣ Clone the repository
bash
Copy code
git clone https://github.com/your-username/vidsnap-ai.git
cd vidsnap-ai
2️⃣ Create a virtual environment
bash
Copy code
python -m venv venv
Activate it:

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Set up your environment variables
Create a .env file in the project root and add:
env
Copy code
OPENAI_API_KEY=your_openai_api_key_here

5️⃣ Run the app
streamlit run app.py


📂 Project Structure
bash
Copy code
vidsnap-ai/
│-- app.py              # Main Streamlit app
│-- requirements.txt    # Python dependencies
│-- utils/              # Helper functions for video processing
│-- README.md           # Project documentation
│-- .env                # API keys (ignored in git)


💡 How It Works

User pastes a YouTube link in the app.

Video is downloaded and audio is extracted.

Audio is transcribed to text using Whisper API.

GPT model generates a summary and key points.

Results are displayed on the web interface.


