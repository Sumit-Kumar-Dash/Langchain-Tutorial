# Langchain-Tutorial

Commands for setting up and running the Langchain tutorial project.
## Prerequisites
- Python 3.8 or higher
- pip (Python package installer)
## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/langchain-tutorial.git
   ```
2. Navigate to the project directory:
   ```bash
   cd langchain-tutorial
   ```

3. Create a virtual environment and activate it:
    - On Windows (PowerShell)
    ```powershell
    python -m venv .venv
    .\.venv\Scripts\Activate.ps1
    ```
    - On Windows (cmd)
    ```cmd
    python -m venv .venv
    .\.venv\Scripts\activate.bat
    ```
    - On macOS/Linux
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set up environment variables:
   - Create a `.env` file in the project root directory.
   - Add your API keys and other necessary configurations in the `.env` file. For example:
     ```
     OPENAI_API_KEY=your_openai_api_key
     GOOGLE_API_KEY=your_google_api_key
     HUGGINGFACE_API_KEY=your_huggingface_api_key
     ```
6. Verify the installation:
   ```bash
   python -c "import langchain; print('Langchain installed successfully!')"
   ```
7. (Optional) Run tests to ensure everything is set up correctly:
   ```bash
   pytest tests/
   ```

8. Freeze the current environment's packages:
   ```bash
   pip freeze > requirements.txt
   ```
9. pipdeptree to visualize dependencies:
   ```bash
   pip install pipdeptree
   pipdeptree
   ```

## Deactivation
10. Deactivate the virtual environment when done:
   ```bash
   deactivate
   ```

   
## Running the Tutorial
1. Run the main tutorial script:
   ```bash
   python main.py
   ```
