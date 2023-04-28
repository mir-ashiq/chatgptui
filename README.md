[![Python application Setup - Chat GPT](https://github.com/paraskuk/chatgptui/actions/workflows/python-app.yml/badge.svg)](https://github.com/paraskuk/chatgptui/actions/workflows/python-app.yml)

# AskGPT

AskGPT is a simple web application that uses the OpenAI API to generate responses to user queries using GPT-3 language model. This application is built using FastAPI and Jinja2Templates for the frontend.

## Requirements

- Python 3.11 or higher
- openai
- FastAPI
- Jinja2Templates

## Installation

1. Clone the repository
2. Install the required packages using `pip install -r requirements.txt`
3. Set the `OPEN_AI_KEY` environment variable with your OpenAI API key.

## Usage

1. Run the application using the command `uvicorn main:app --reload`.
2. Navigate to `http://localhost:8000/` on your browser to access the application.
3. Enter your query in the input field and click on the `Submit` button to generate a response.

## Note

Make sure to set the `OPEN_AI_KEY` environment variable before running the application, as this is required for the OpenAI API to function properly.

## License

This project is not licensed for commercial use due to having been partially generated by Chat GPT.

## Disclaimer

This project is for demonstration of Chat GPT capabilities and should not be used wholly or partly in 
any customer project as the code generated by GPT may infringe copyright. Chat GPT code can also be 
identified with certain tools of which research is ongoing.
