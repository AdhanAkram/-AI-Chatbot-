🤖 AI Chatbot — Adhan Akram
A conversational AI chatbot built with Python and Streamlit, powered by OpenAI's GPT-3.5-turbo model. Features a clean chat interface with customizable settings.

✨ Features

💬 Real-time AI conversation using GPT-3.5-turbo
⚙️ Sidebar settings — customize system prompt, temperature, and max tokens
🧠 Chat history maintained during session
🔄 Clear chat and reset functionality
🔐 Secure API key handling via .env file


🛠️ Tech Stack
TechnologyPurposePython 3.10+Core programming languageStreamlitWeb UI frameworkOpenAI APIGPT-3.5-turbo language modelpython-dotenvSecure environment variable management

📁 Project Structure
ai-chatbot/
│
├── app.py               # Main chatbot application
├── requirements.txt     # Python dependencies
├── .env                 # API key (never commit this)
├── .gitignore           # Ignores venv and .env
└── README.md            # Project documentation

⚙️ Installation & Setup
1. Clone the repository
bashgit clone https://github.com/yourusername/ai-chatbot.git
cd ai-chatbot
2. Create and activate virtual environment
bashpython -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate
3. Install dependencies
bashpip install -r requirements.txt
4. Set up your API key
Create a .env file in the root folder:
OPENAI_API_KEY=your_openai_api_key_here
Get your free API key at: https://platform.openai.com
5. Run the app
bashstreamlit run app.py
Open your browser at http://localhost:8501 🎉

🌐 Deploy for Free (Streamlit Cloud)

Push this project to GitHub
Go to share.streamlit.io
Connect your GitHub account
Select this repo and set app.py as the main file
Add your OPENAI_API_KEY in the Secrets section
Click Deploy — your chatbot is live!


📌 Usage

Type any message in the chat input at the bottom
Use the sidebar to:

Change the assistant's personality via system prompt
Adjust response length with max tokens slider
Control creativity with the temperature slider
Clear the chat history anytime




🔐 Security Notes

Never commit your .env file to GitHub
The .gitignore file already excludes it
Rotate your API key if it gets accidentally exposed


👨‍💻 About the Developer
Adhan Akram — AI & Machine Learning Developer

📧 sardaradhan85@gmail.com
🔗 LinkedIn Profile
💻 GitHub
