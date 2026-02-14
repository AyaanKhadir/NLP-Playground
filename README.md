---

# 🚀 NLP Nexus Pro: Advanced Text Analysis Playground

**NLP Nexus Pro** is a comprehensive, visually-driven natural language processing suite. Built with **Gradio** and **NLTK**, it transforms raw text into actionable insights through a modern, interactive web interface.

This project is designed as a portfolio-ready demonstration of full-stack NLP integration—combining statistical analysis, machine learning heuristics, and dynamic data visualization.

---

## ✨ Key Features

### 🔍 Core Analytics

* **Named Entity Recognition (NER):** Visual highlighting of People, Organizations, Locations, and Dates using custom HTML rendering.
* **Sentiment & Subjectivity:** Real-time emotional polarity tracking visualized via **Plotly gauge charts**.
* **Extractive Summarization:** Frequency-based algorithm with user-controlled depth sliders.
* **Keyword Extraction:** High-precision keyphrase identification using the **YAKE** algorithm.

### 📊 Advanced Visualizations

* **Readability Fingerprint:** A multi-metric radar chart (Flesch-Kincaid, Gunning Fog, etc.) to assess text complexity.
* **POS Distribution:** Interactive bar charts showing Part-of-Speech tag density.
* **Word Clouds:** Beautifully rendered frequency maps with automated stop-word filtration.

### 📂 Technical Utility

* **Multi-Format Support:** Process raw text, `.txt`, or `.pdf` files via **PyPDF2**.
* **Data Export:** Comprehensive token logs in DataFrames and exportable JSON metadata.
* **Modern UI:** Responsive layout featuring the Gradio 'Soft' theme and custom CSS.

---

## 🛠️ Tech Stack

| Category | Tools & Libraries |
| --- | --- |
| **Interface** | Gradio, HTML5/CSS3 |
| **NLP Engine** | NLTK, TextBlob, YAKE, Textstat |
| **Visualization** | Plotly, WordCloud, Matplotlib |
| **Data Science** | Pandas, NumPy |
| **Document Parsing** | PyPDF2 |

---

## 🚀 Getting Started

### Prerequisites

* Python 3.9 or higher
* pip (Python package manager)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/AyaanKhadir/nlp-nexus-pro.git
cd nlp-nexus-pro

```


2. **Set up a virtual environment (Recommended)**
```bash
python -m venv venv
# macOS/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate

```


3. **Install dependencies**
```bash
pip install -r requirements.txt

```



### Execution

Run the local development server:

```bash
python app.py

```

The application will be available at: `http://127.0.0.1:7860`

---

## 📈 Roadmap & Future Enhancements

* [ ] **Transformer Integration:** Swap NLTK for Hugging Face `transformers` (BERT/RoBERTa) for deep-learning-based NER and Sentiment.
* [ ] **Dependency Parsing:** Interactive tree visualizations using `spaCy` and `displaCy`.
* [ ] **Topic Modeling:** Integration of LDA or BERTopic for thematic discovery in large documents.
* [ ] **Multilingual Support:** Expanding tokenization and POS tagging for 10+ languages.

---

## 👨‍💻 Author

**Ayaan Khadir**
*B.Tech + M.Tech in Artificial Intelligence & Data Science*
📍 Hyderabad, India

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

*Built with ❤️ for the NLP community in 2026.*
