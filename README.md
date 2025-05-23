# AILed Analysis of Financial Statement

A Flask-based financial analysis platform that authenticates users, analyzes company data, computes financial ratios, and generates natural language insights using OpenAI's GPT model.

## Features

- User authentication system  
- Financial data analysis and ratio computation  
- Natural language generation of financial insights using OpenAI's GPT model  
- Interactive web interface built with Flask  

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Python 3.x  
- pip (Python package installer)  
- Docker and Docker Compose (optional, for containerized setup)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/omidnouri/AILed-analysis-of-financial-statement.git
   cd AILed-analysis-of-financial-statement

2. **Set up the data file:**

   After cloning the repository, you need to add a data file to the project directory.

   - Locate the file named `FTSE100_AR_NLP_FACTORS` on your system.
   - Rename it to `data.csv`.
   - Move or copy the renamed `data.csv` file into the root directory of the cloned project (`AILed-analysis-of-financial-statement/`).

3. **Install required Python packages:**

   Use the `requirements.txt` file to install the necessary dependencies:

   ```bash
   pip install -r requirements.txt

### Configuration

Before running the application, you need to add your OpenAI API key to the `config.json` file.

Open `config.json` in the root directory and update the `openai_api_key` field:

# Running the Application

Using Flask:

```bash
flask run
```

By default, the application will be available at [http://127.0.0.1:5000](http://127.0.0.1:5000).

# Programme structure
```
AILed-analysis-of-financial-statement/
├── __pycache__/
├── static/
│   └── js/
├── templates/
├── .gitignore
├── README.md
├── app.py
├── archive.json
├── config.json
├── requirements.txt
├── search_cache.json
└── data.csv
```
