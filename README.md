# Socratic Learning Assistant for Data Structures 🧠
This is an AI-powered learning assistant designed to help users explore and understand data structures (such as arrays, trees, graphs, and linked lists) using the Socratic method. Built using Streamlit and Google Generative AI (Gemini 1.5 Pro), the assistant guides learners by asking probing questions rather than providing direct answers, encouraging deeper understanding.

## Features
- **Socratic Teaching:** The assistant responds to user input by asking follow-up questions, helping learners arrive at the correct conclusions on their own.
- **Conversation Memory:** The assistant remembers the context of the conversation and uses it to ask relevant, connected questions throughout the interaction.
- **Simple Interface:** The user-friendly Streamlit-based interface makes interacting with the assistant intuitive and engaging.
- **Powered by Google Generative AI:** Utilizing the latest in AI technology (Gemini 1.5 Pro), the assistant provides intelligent, context-aware responses to guide learning.

## Installation
1. **Clone the repository:**

    ```bash
    git clone https://github.com/shaadclt/Socratic-Learning-Assistant.git
    cd Socratic-Learning-Assistant
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your Google API key in the Streamlit secrets file.**
    Create a `.streamlit/secrets.toml` file and add your API key:

    ```toml
    [GOOGLE_API_KEY]
    GOOGLE_API_KEY = "your-google-api-key-here"
    ```

5. Running the App
    To launch the app, run:
    
    ```bash
    streamlit run app.py
    ```

The app will be available at http://localhost:8501.

## Usage
1. Type any question related to data structures in the input field.
2. The assistant will respond with a follow-up question, guiding you through the learning process.
3. Continue the conversation to explore different concepts, clarify doubts, and deepen your understanding.

## Customization
You can modify the Socratic teaching style or add more features by customizing the LangChain prompt and memory settings in the code.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request to improve the app or add new features.

## License
This project is licensed under the [MIT License](LICENSE.txt).
