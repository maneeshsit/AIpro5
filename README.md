# Initialize the project
uv init .
# Add the dependencies to the project
uv add python-dotenv langgraph "langchain[anthropic]" ipykernel
# Run the project chatbot
uv run main.py
