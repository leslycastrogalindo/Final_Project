#  Local AI Personal Coach

A reasoning-based goal management system served locally. This tool helps you break down long-term ambitions into daily tasks using a local LLM for personalized feedback and pattern analysis.

##  Project Structure

- **/backend**: FastAPI server, SQLite database, and AI reasoning logic.
- **/frontend**: React-based dashboard for goal tracking and reflections.

##  Getting Started (Local Setup)

### 1. Prerequisites
* **Python 3.10+**
* **Node.js**
* **Ollama**: [Download here](https://ollama.com/) and run `ollama pull llama3`.

### 2. Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install fastapi uvicorn requests
uvicorn main:app --reload
