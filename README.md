# QueryMind

QueryMind is an AI-powered data analysis agent that lets you upload CSV files and interactively ask questions about your data. It uses OpenAI's GPT-4o model to generate Python (pandas/matplotlib) code, execute it, and provide natural language explanations and visualizations.

## Features

- Upload CSV files and preview your data.
- Ask questions in natural language about your dataset.
- Automatically generates and executes Python code to answer your queries.
- Supports both textual and visual (plot/chart) responses.
- Provides concise, user-friendly explanations for results.
- Powered by OpenAI GPT-4o and Streamlit.

## Getting Started

### Prerequisites

- Python 3.8+
- [OpenAI API key](https://platform.openai.com/account/api-keys)

### Installation

1. Clone this repository.
2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    pip install streamlit openai matplotlib pandas
    ```
3. Add your OpenAI API key to `.streamlit/secrets.toml`:
    ```toml
    OPENAI_API_KEY = "your-openai-api-key"
    ```

### Running the App

```sh
streamlit run [data_analysis.py](http://_vscodecontentref_/1)
