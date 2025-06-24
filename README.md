💬 BAPOLAIC AI Chatbot
BAPOLAIC (Batam Politeknik Artificial Intelligence Chatbot) is a smart, interactive web-based AI chatbot developed to assist users through both voice and document-based interactions. Built using modern web technologies—HTML, CSS, and JavaScript for the frontend—this project leverages Python Flask as the backend framework to handle logic and API integrations.

🔧 Key Features:
🔤 OCR (Optical Character Recognition): BAPOLAIC can intelligently extract and recognize text from image files and scanned documents (e.g., JPG, PNG, PDF, DOCX), allowing users to process written data efficiently.

🎙️ Voice Assistant: Equipped with voice interaction capability, the chatbot allows users to communicate via speech and receive voice-based responses, providing a more natural and accessible user experience.

🤖 Gemini API Integration: Integrated with Google's Gemini API, the chatbot gains powerful generative AI capabilities to understand queries, generate intelligent responses, and process natural language inputs with high accuracy.

🌐 Tech Stack
Frontend: HTML5, CSS3, JavaScript

Backend: Python (Flask)

AI & NLP: Google Generative AI (Gemini), Langchain

Voice Tech: Web Speech API (for speech recognition), gTTS (Google Text-to-Speech)

OCR Libraries: PyTesseract, PyPDF2, python-docx, PIL

📌 Purpose
This chatbot was developed as part of an academic project at Politeknik Negeri Batam, aiming to explore the integration of AI, document automation, and voice interfaces in web applications. It serves both as a virtual assistant and a productivity tool that simplifies human-computer interaction in real-time.

🚀 Getting Started
To try out BAPOLAIC AI Chatbot on your own device, you can simply download or clone this repository and run the application on your local machine.

✅ Prerequisites
Before running the project, make sure you have the following installed:

Python 3.8+

Pip (Python package manager)

Git (optional, if cloning from GitHub)

📥 Installation Steps
bash
Copy
Edit
# 1. Clone the repository
git clone [https://github.com/your-username/BAPOLAIC-V1.0.git](https://github.com/RivalFHRJ24/BAPOLAIC-V-1.0.git)

# 2. Navigate to the project directory
cd BAPOLAIC-V1.0

# 3. (Optional but recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Set your Gemini API key
export GOOGLE_API_KEY="your-api-key-here"  # On Windows: set GOOGLE_API_KEY=your-api-key-here

# 6. Run the Flask server
python app.py
Once the server is running, open your browser and go to:

cpp
Copy
Edit
http://127.0.0.1:5000/
You should now see the BAPOLAIC AI Chatbot interface.

🔑 How to Get Your Gemini API Key
To enable BAPOLAIC’s advanced AI capabilities, you will need an API key from Google AI Studio (Gemini).

Steps to generate the API key:
Go to the official Google AI Studio website. this link [https://aistudio.google.com/app/apikey]

Sign in using your Google account.

Navigate to the API Keys section.

Click "Create API Key".

Copy the generated key.

In your local project, set the environment variable GOOGLE_API_KEY to the key you received.

🔒 Important: Keep your API key private and never share it publicly.
