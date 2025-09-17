# AI Learning Python Notebooks

A collection of Jupyter notebooks for learning and experimenting with AI frameworks and Large Language Models (LLMs), including OpenAI Agents, LangChain, and other popular AI tools.

## Setup

1. **Install uv** (if not already installed):

   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. **Install dependencies**:

   ```bash
   uv sync
   ```

3. **Set up environment variables**:

   Create a `.env` file in the project root and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Open notebooks**: Launch VS Code or Jupyter and select the Python kernel from the virtual environment created by uv when opening notebook files.
