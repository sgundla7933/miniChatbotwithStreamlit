# miniChatbotwithStreamlit

A simple chatbot built using Streamlit for the UI and OpenAI API for the backend. The chatbot takes user input, interacts with OpenAI's GPT models, and generates responses in real-time.

**Features**
Interactive chat interface using Streamlit.
Sends user prompts to OpenAI API and streams responses.
Supports streaming responses for real-time conversation experience.
Tracks conversation history within the session.

**Prerequisites**
Python 3.7+
OpenAI API Key (sign up for one at OpenAI)
Streamlit library
Dotenv for environment variable management

**Installation**
1. Clone the repository:
git clone https://github.com/your-username/miniChatbotwithStreamlit.git

2. Navigate to the project directory:
cd miniChatbotwithStreamlit

3. Install required dependencies:
pip install -r requirements.txt

4. Add your OpenAI API Key:
Create a .env file in the root directory.
Add the following line to your .env file:

OPENAI_API_KEY=your-openai-api-key

**How to Run**

1. Start the Streamlit app:
streamlit run chatbot.py

2. Open your browser and navigate to:
http://localhost:8501

**Usage**
Enter your prompt in the input field, and the chatbot will respond with an AI-generated answer.
The conversation history is maintained within the session.
