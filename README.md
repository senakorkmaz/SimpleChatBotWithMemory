#  Simple ChatBot With Memory

This is a simple chatbot application built using **LangChain**, **Streamlit**, and **OpenAI** APIs. The chatbot supports memory, allowing it to remember previous messages during a conversation and respond in a more contextual way.

##  Features

- Memory-enabled conversation using `ConversationBufferMemory`
- OpenAI integration for language generation
- Clean and minimal code structure
- Environment variable support for API key

##  Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- Python 3.12+

## 📁 Project Structure

```
SimpleChatBotWithMemory/
│
├── main.py                # Streamlit application file
├── requirements.txt       # Python dependencies
└── .env                   # OpenAI API Key stored here (not committed)
```

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/senakorkmaz/SimpleChatBotWithMemory.git
cd SimpleChatBotWithMemory
```

### 2. Create a Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
(Optional for tracing)
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=SIMPLECHATBOT
```

### 5. Run the App

```bash
python main.py
```


## 📌 Notes

- You can switch between different LLMs provided by OpenAI by modifying the `ChatOpenAI` parameters.
- Streamlit automatically reloads on file save during development.


---

Feel free to contribute or fork this repo!
