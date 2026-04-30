# AI Projects Repository

This repository contains a collection of AI-driven applications built using the OpenAI API and modern NLP techniques. The projects focus on applying language models and data processing pipelines to practical use cases, including content generation, prompt engineering, interactive workflows, and financial text analysis.

---

# Projects

## AI Recipe Generator
Generates structured recipes from randomly selected ingredients using an OpenAI model.

### Key Features
- Random ingredient selection from a predefined list  
- Prompt-based recipe generation  
- Structured output including ingredients and preparation steps  

**File:** `ai_recipe_generator.ipynb`

---

## Interactive Storytelling with OpenAI
An interactive storytelling system where users guide the narrative and the model dynamically continues the story.

### Key Features
- Context-aware story generation based on user input  
- Prompt conditioning for narrative control  
- Interactive loop for evolving storylines  
- Chapter-based structuring of generated text  

**File:** `interactive_storytelling.ipynb`

---

## Financial Risk Assessment using NLP
Analyzes financial news articles to estimate sentiment-driven risk scores for companies using natural language processing techniques.

### Key Features
- Web scraping of financial news using RSS feeds  
- Sentiment analysis using transformer-based models  
- Named Entity Recognition (NER) using SpaCy  
- Aggregated risk scoring based on sentiment trends  
- Data visualization of comparative company risk  

**File:** `financial_risk_assessment_nlp.ipynb`

---

# Setup

### Clone the repository:
```bash
git clone https://github.com/rahulkumar2023/ai-projects.git
cd ai-projects
````

### Install dependencies:

```bash
pip install openai transformers torch spacy pandas numpy matplotlib beautifulsoup4 requests yfinance
```

### Download SpaCy model:

```bash
python -m spacy download en_core_web_sm
```

### Set your OpenAI API key:

#### Mac/Linux

```bash
export OPENAI_API_KEY="your-api-key"
```

#### Windows (PowerShell)

```powershell
$env:OPENAI_API_KEY="your-api-key"
```

---

# Concepts Demonstrated

* Prompt engineering and response conditioning
* Generative text applications using language models
* Interactive user-driven workflows
* NLP pipelines (sentiment analysis, entity recognition)
* Data extraction and processing from web sources
* Structuring and analyzing unstructured text data

---

# Tech Stack

* Python
* OpenAI API
* Hugging Face Transformers
* SpaCy
* Jupyter Notebook

---

# Notes

* An OpenAI API key is required for OpenAI-based notebooks
* Ensure your account has active credits or billing enabled
* Outputs may vary depending on prompt design and model behavior
* The storytelling project requires user input during execution
* The financial risk project uses general-purpose NLP models (not finance-specific)

---

# Future Improvements

* Convert notebooks into deployable applications (e.g., Streamlit)
* Introduce persistent state for multi-step interactions
* Improve user interface and usability
* Integrate finance-specific NLP models (e.g., FinBERT)
* Expand with additional AI-based use cases

---

# Disclaimer

This repository is intended for educational and experimental purposes. AI-generated outputs may not always be accurate or appropriate and should be reviewed before use in production settings.

---

# Summary

This repository demonstrates practical applications of modern AI systems, focusing on building simple, effective tools powered by language models and NLP techniques while showcasing both technical implementation and applied problem-solving.
