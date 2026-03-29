# AI Research Paper Summarizer 📄

An intelligent Streamlit web application that transforms lengthy, complex research papers (PDFs) into digestible summaries, interactive flowcharts, and AI-powered insights.

## ✨ Features

- **Instant Summarization** — Distills entire papers into abstracts, key points, and conclusions in seconds.
- **AI Analysis** — Digs deeper into the main problem, proposed solutions, strengths, limitations, and real-world applications.
- **Chat with Paper** — An interactive Q&A chatbot powered by the full context of your uploaded paper.
- **Interactive Flowchart** — Dynamically maps the paper's core structure into a draggable, zoomable Mermaid.js flowchart.
- **PDF Exports** — Download summaries, analysis reports, and flowcharts as PDF files for offline use.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- A free [Google Gemini API Key](https://aistudio.google.com/app/apikey)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SID-2006/AI-Research-Paper-Summarizer.git
   cd AI-Research-Paper-Summarizer
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a `.env` file** in the project root and add your API key:
   ```
   GOOGLE_API_KEY=your_gemini_api_key_here
   ```
   > ⚠️ This step is mandatory. The app will not work without a valid API key.

4. **Run the app:**
   ```bash
   streamlit run app.py
   ```

5. Open your browser at `http://localhost:8501` and start uploading papers!

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) — Frontend framework
- [Google Gemini API](https://ai.google.dev/) — AI summarization & analysis
- [pdfplumber](https://github.com/jsvine/pdfplumber) — PDF text extraction
- [Mermaid.js](https://mermaid.js.org/) — Flowchart rendering
- [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) — Client-side PDF generation