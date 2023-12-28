![image](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F7c06c5d5-d8b7-4499-b202-cc9826c489e9_900x701.png)

![dotenv 0.20.0](https://img.shields.io/badge/dotenv-0.20.0-brightgreen?style=flat)
![Streamlit 1.10.0](https://img.shields.io/badge/Streamlit-1.10.0-blue?style=flat)
![Google API](https://img.shields.io/badge/Google_API-latest-yellow?style=flat)
![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python&logoColor=white)


# Gemini LLM Application

This project implements a question-and-answer application using the Gemini Pro model from Google's Generative AI library, integrated into a Streamlit web application. It allows users to interact with the Gemini model to get responses to their queries.

## Chatbot Interface
[https://geminichatbot.streamlit.app/](https://geminichatbot.streamlit.app/).
![](https://github.com/abh2050/gemini-google/blob/main/pic.png)


## Features

- **Environment Variable Loading**: Uses `dotenv` to load environment variables securely.
- **Gemini Pro Model Integration**: Leverages the advanced capabilities of the Gemini Pro model from Google Generative AI.
- **Streamlit Interface**: Provides a user-friendly web interface built with Streamlit for interacting with the model.
- **Interactive Chat History**: Maintains a session-based chat history for each user.

## Getting Started

### Prerequisites

- Python 3.x
- Streamlit
- Google Generative AI library

### Installation

1. Clone the repository.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file with your Google API key:

   ```dotenv
   GOOGLE_API_KEY=your_google_api_key_here
   ```

### Usage

Run the Streamlit application:

```bash
streamlit run your_script_name.py
```

Navigate to `http://localhost:8501` or the provided URL to access the application.

## Usage Instructions

- Enter your question in the text input field.
- Click "Ask the Question" to get a response from the Gemini model.
- The chat history and responses will be displayed on the page.

## Deployment

The application is deployed at [https://geminichatbot.streamlit.app/](https://geminichatbot.streamlit.app/).

## Contributing

Contributions, issues, and feature requests are welcome!

## License

[MIT License](LICENSE)

## Acknowledgements

- Google Generative AI
- Streamlit
- dotenv
