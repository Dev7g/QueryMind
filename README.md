# QueryMind 🚀

**QueryMind** is your AI-powered data analysis companion. Upload any CSV file and chat with your data—get instant insights, visualizations, and code explanations, all powered by OpenAI GPT-4o and Streamlit.

---

## ✨ Features

- **Upload & Preview**: Instantly upload and preview your CSV data.
- **Conversational Analysis**: Ask questions in plain English—no coding required!
- **Automatic Code Generation**: See the Python (pandas/matplotlib) code generated for your queries.
- **Visual Insights**: Get beautiful charts and plots on demand.
- **Smart Explanations**: Receive concise, natural language explanations for every result.
- **Powered by OpenAI GPT-4o**: Leverages the latest in AI for accurate, context-aware answers.

---

## 🚀 Quick Start

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/QueryMind.git
cd QueryMind
```

### 2. Install Dependencies

```sh
pip install -r requirements.txt
pip install streamlit openai matplotlib pandas
```

### 3. Configure OpenAI API Key

Create a file at `.streamlit/secrets.toml` and add:

```toml
OPENAI_API_KEY = "your-openai-api-key"
```

### 4. Launch the App

```sh
streamlit run data_analysis.py
```

Open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 🖥️ Usage

1. **Upload** your CSV file.
2. **Review** the dataset summary and suggested questions.
3. **Chat**: Ask questions like:
   - "Show the distribution of ages."
   - "What is the average salary?"
   - "Plot sales by region."
4. **Explore**: View results, explanations, and generated code.

---

## 📁 Project Structure

| File/Folder                | Purpose                                      |
|----------------------------|----------------------------------------------|
| `data_analysis.py`         | Main Streamlit application                   |
| `.streamlit/secrets.toml`  | Store your OpenAI API key                    |
| `.devcontainer/`           | VS Code/Codespaces dev container config      |
| `LICENSE`                  | MIT License                                  |
| `README.md`                | Project documentation                        |

---

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) – Fast, beautiful web apps for data science
- [OpenAI GPT-4o](https://platform.openai.com/docs/models/gpt-4o) – State-of-the-art language model
- [pandas](https://pandas.pydata.org/) – Data analysis library
- [matplotlib](https://matplotlib.org/) – Plotting and visualization

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🙌 Acknowledgements

- Inspired by the power of conversational AI and data science.
- Created by [Dev7g](https://github.com/Dev7g).

---

> **QueryMind** – Let your data speak!
