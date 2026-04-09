# Private Data Chatbot

A web-based chatbot that summarizes and answers questions about private documents using generative AI.

## Features

- Upload and process private documents
- Generate concise summaries
- Ask questions about document content
- Browser-based interface
- Flask backend with document processing pipeline

## Tech Stack

- Python
- Flask
- HTML / CSS / JavaScript
- Generative AI / Hugging Face / OpenAI / Watson (edit to match your app)

## Project Structure

```text
private-data-chatbot/
├── README.md
├── requirements.txt
├── Dockerfile
├── LICENSE
├── .gitignore
├── server.py
├── worker.py
├── static/
└── templates/
```

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/private-data-chatbot.git
cd private-data-chatbot
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run the App

```bash
python server.py
```

Then open the local URL shown in the terminal.


## Limitations

- Performance depends on document quality and size
- Responses may vary depending on the underlying model
- Not intended for highly sensitive production deployments without additional security controls

## Future Improvements

- Better retrieval pipeline
- PDF / DOCX support
- Authentication
- Deployment
- Citation support

## License

MIT
