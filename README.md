# End-To-End-Gemini-Project
# Q&A Chatbot

This project is a Q&A chatbot application that uses the Gemini model from Google Generative AI. The application is built using Streamlit for the web interface and supports both text-based and image-based queries.

## Project Structure

- `app.py`: Main application file for text-based Q&A using the Gemini model.
- `chat.py`: Alternative implementation for text-based Q&A with streaming responses.
- `qachat.py`: Enhanced text-based Q&A application with chat history functionality.
- `vision.py`: Application for image-based Q&A using the Gemini Vision model.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Project documentation.

## Setup

1. Clone the repository.
2. Create a `.env` file in the root directory and add your Google API key:
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```
3. Install the required dependencies:
    ```sh
    pip install -r [requirements.txt](http://_vscodecontentref_/1)
    ```

## Running the Applications

### Text-Based Q&A (app.py)

To run the text-based Q&A application:
```sh
streamlit run [app.py](http://_vscodecontentref_/2)