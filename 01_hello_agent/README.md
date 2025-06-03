uv init 01_hello_agent
cd 01_hello_agent
uv venv
uv add openai-agents python-dotenv
.venv\Script\activate

uv run main.py