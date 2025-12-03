
# Spotify DB Project (Full)

Files:
- spotify_db_setup.py  : Python script to create schema and load CSV into MySQL.
- ai_agent.py          : Skeleton for LangChain text-to-SQL agent (template).
- spotify_project.ipynb: Jupyter Notebook with steps and examples.
- .env.example         : Example environment file.

## Quick start

1. Install dependencies:
   ```
   pip install pandas sqlalchemy pymysql python-dotenv tqdm nbformat
   pip install langchain openai   # if you plan to use ai_agent.py
   ```

2. Copy your dataset.csv into this folder or set CSV_PATH in .env.

3. Create `.env` based on `.env.example`.

4. Run:
   ```
   python spotify_db_setup.py
   ```

5. Use `ai_agent.py` as a template to connect LangChain -> SQLDatabaseChain.

Note: The ai_agent.py is a template. To run a real LangChain+Gemini/OpenAI agent, follow LangChain docs and set API keys.

