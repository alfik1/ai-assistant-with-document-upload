# OpenAI Assistants API Chat Application



This is a simple chat application that integrates with OpenAI's Assistants API to generate responses based on user inputs and uploaded documents. The application allows users to upload files, scrape website content, and initiate a chat session with the AI assistant.

## Features

- **File Upload**: Users can upload PDF documents containing information relevant to their queries.
- **Web Scraping**: Users can provide a URL to scrape content from a website, which is then organized into a PDF document.
- **Chat Interface**: Once files are uploaded, users can initiate a chat session with the AI assistant to ask questions or seek information.
- **Citation Support**: The application supports the extraction and formatting of citations from assistant responses, making it easier for users to reference information.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:


```
git clone https://github.com/<username>/openai-assistants-chat.git
```

2. Navigate to the project directory:


```
cd openai-assistants-chat
```

3. Install the required dependencies:


```
pip install -r requirements.txt
```

4. Set up your OpenAI API key by creating an account on the OpenAI platform and replacing the `api_key` variable in the code with your API key.

5. Run the Streamlit application:

```
streamlit run app.py

```
## Usage

1. Upon running the application, you will see a sidebar with configuration options and additional features.
2. Configure your OpenAI API key in the sidebar.
3. Use the sidebar to upload files or provide a website URL for scraping.
4. Click the corresponding buttons to initiate the scraping/upload process.
5. Once files are uploaded, click "Start Chat" to begin a conversation with the AI assistant.
6. Enter your queries in the chat interface and receive responses from the assistant.

## Credits

This application was created using Streamlit for the user interface and OpenAI's Assistants API for natural language processing and responses.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


