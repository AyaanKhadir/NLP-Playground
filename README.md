```markdown
# NLP Nexus Pro – Advanced NLP Text Analysis Playground

A powerful, visually rich, and interactive **NLP demo application** built with **Gradio** and **NLTK**, designed to showcase advanced natural language processing techniques in a clean, modern interface.

This project demonstrates a wide range of NLP capabilities — from tokenization and lemmatization to **Named Entity Recognition (NER)** with visual highlighting, **sentiment analysis** with gauges, **readability visualization** using radar charts, **word clouds**, keyword extraction, and extractive summarization — all in one unified, portfolio-ready application.

Perfect for:
- Portfolio showcase
- Teaching NLP concepts
- Experimenting with text analysis
- Demonstrating Gradio + Plotly + NLTK integration

## ✨ Features

- **Interactive web interface** powered by Gradio
- **Input options**: Paste text or upload `.txt` / `.pdf` files
- **Named Entity Recognition (NER)** with colorful HTML highlighting
- **Sentiment Analysis** visualized as a beautiful gauge (Polarity)
- **POS Tag Distribution** – top tags bar chart (Plotly)
- **Readability Fingerprint** – radar chart showing multiple readability metrics
- **Word Cloud** generation (cleaned, stopwords removed)
- **Keyword Extraction** using YAKE
- **Extractive Summarization** (control number of sentences)
- **Full token & POS log** in a dataframe
- **Exportable JSON** metadata (sentiment assessments)
- Clean stats overview (sentences, words, complex words)
- Modern UI with tabs, responsive layout, and soft theme

## 🖼️ Screenshots



1. **Main Interface** – input + stats overview  
2. **NER Highlighting** – colorful entity visualization  
3. **Sentiment Gauge** – emotional polarity indicator  
4. **Readability Radar + POS Bar Chart**  
5. **Word Cloud + Keywords & Summary**

## 🚀 Live Demo

*(If you deploy it – add the link here)*  
Example: https://huggingface.co/spaces/your-username/nlp-nexus-pro

## 📋 Requirements

```text
gradio
nltk
textblob
textstat
yake
PyPDF2
pandas
plotly
wordcloud
numpy
```

Install all dependencies with:

```bash
pip install -r requirements.txt
```

## 🛠️ Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/AyaanKhadir/nlp-nexus-pro.git
cd nlp-nexus-pro
```

### 2. Install dependencies

```bash
# Recommended: use a virtual environment
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows

pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

The app will open in your browser at:  
**http://127.0.0.1:7860**

### 4. Try it out

- Paste any text (news article, paragraph, PDF content, etc.)
- Or upload a `.txt` or `.pdf` file
- Adjust **Summary Depth** slider
- Click **Run Full Diagnostic**

## 🧠 Technologies Used

| Category              | Tools / Libraries                              |
|-----------------------|------------------------------------------------|
| Web Interface         | Gradio                                         |
| NLP Processing        | NLTK, TextBlob, YAKE, textstat                 |
| Visualization         | Plotly (gauge, bar, radar), WordCloud          |
| File Handling         | PyPDF2                                         |
| Data Handling         | pandas, numpy                                  |
| UI Styling            | HTML + CSS (inline), Gradio Soft theme         |

## 🔍 Key NLP Components Implemented

- **Tokenization** — word & sentence level
- **POS Tagging** — using NLTK’s averaged perceptron tagger
- **Named Entity Recognition** — person, organization, location, date, etc.
- **Lemmatization** — (can be extended easily)
- **Sentiment Analysis** — polarity & subjectivity via TextBlob
- **Readability Scores** — Flesch Reading Ease, Flesch-Kincaid, difficult words count
- **Keyword Extraction** — YAKE (Yet Another Keyword Extractor)
- **Extractive Summarization** — frequency-based sentence selection
- **Word Cloud** — cleaned and visually appealing

## 📈 How to Extend / Improve

Some ideas for future versions:

- Add **dependency parsing** visualization (using spaCy + displaCy)
- Add **topic modeling** (LDA / BERTopic preview)
- Support **multiple languages** (basic multilingual tokenizers)
- Add **text comparison** (similarity, diff between two documents)
- Add **export to PDF** or **CSV**
- Integrate **Hugging Face** models for more powerful summarization / NER
- Add **dark mode** toggle / custom themes
- Deploy on **Hugging Face Spaces** or **Streamlit Community Cloud**

## 🙌 Acknowledgments

- Gradio team – for the fantastic UI framework
- NLTK team – for the classic and reliable NLP tools
- Plotly – for beautiful interactive visualizations
- YAKE authors – for excellent keyword extraction

## 📄 License

MIT License

Feel free to use, modify, and share this project — attribution appreciated!

## 👨‍💻 Author

**Ayaan Khadir**  
B.Tech + M.Tech in Artificial Intelligence & Data Science  
Hyderabad, India  
GitHub: [AyaanKhadir](https://github.com/AyaanKhadir)

---

Built with ❤️ for learning, teaching, and showcasing NLP in 2026
```
