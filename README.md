# Multi-Document ChatBot 🤖
A powerful chatbot application that allows users to interact with multiple PDF documents using OpenAI's GPT models, powered by LangChain and Streamlit.

## Features
- 📚 Multi-document PDF processing
- 💬 Interactive chat interface with PDF content
- 📊 PDF analytics including:
  - Word count
  - Character count
  - VADER sentiment analysis
- 🎯 Customizable chatbot settings:
  - Model selection
  - Personality types
  - Temperature control
- 🔒 Secure OpenAI API authentication
- 🐳 Docker support for easy deployment

## Prerequisites
- Python 3.8+
- OpenAI API key
- Docker (optional)

## Installation

### Local Setup
1. Clone the repository:
```bash
git clone https://github.com/MohamedKotb7/Chatbot_PDF.git
cd multi-document-chatbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run main.py
```

### Docker Setup
# Build the Docker image
docker build -t streamlit-pdf-chat .

# Run the container
docker run -p 8501:8501 streamlit-pdf-chat
The application will be available at `http://localhost:8501`

## Configuration
1. Get your OpenAI API key from [OpenAI Platform](https://platform.openai.com/account/api-keys)
2. Enter your API key in the application's authentication section

## Usage
1. Upload one or more PDF documents
2. Configure chatbot settings (optional):
   - Select GPT model
   - Choose personality type
   - Adjust temperature
3. Enable PDF analytics (optional):
   - Word count
   - Character count
   - VADER sentiment analysis
4. Start chatting with your documents!

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
