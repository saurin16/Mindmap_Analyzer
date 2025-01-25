
# 📚 AI PDF to Interactive Mindmap Converter

A streamlined tool to convert PDFs into interactive hierarchical mindmaps using the power of AI. This project extracts text from PDF documents, generates structured markdown for mindmaps, and renders them in a dynamic, interactive format for enhanced understanding.

---

## 🚀 Features

### ✅ Core Capabilities:
- **PDF Text Extraction**: Converts uploaded PDFs into text with accurate parsing.
- **AI-Generated Mindmaps**: Uses Gemini AI to create structured, meaningful mindmaps in markdown format.
- **Interactive Visualization**: Displays mindmaps using `Markmap` with dynamic interactivity and customization.
- **Markdown Download**: Offers downloadable markdown files for future use.

---

## ⚙️ Tech Stack

- **Frontend**: Streamlit - A sleek, responsive UI framework for Python.
- **AI**: Google Gemini AI (Generative AI) - Content generation for summarization and mindmap creation.
- **PDF Parsing**: PyPDF2 - Extracts text from PDF documents.
- **Visualization**: Markmap - Creates interactive and visually appealing mindmaps.
- **Components**: Streamlit Custom Components - For embedding Markmap visualizations in the app.

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/interactive-mindmap.git
cd interactive-mindmap
```

### 2. Set Up Environment
Install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3. Configure API Key
- **Option 1**: Set the API key as an environment variable:
  ```bash
  export GOOGLE_API_KEY=your_api_key_here  # macOS/Linux
  set GOOGLE_API_KEY=your_api_key_here    # Windows
  ```

- **Option 2**: Use a `.env` file (requires `python-dotenv`):
  1. Create a `.env` file in the project root:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```
  2. Add the following line to your script:
     ```python
     from dotenv import load_dotenv
     load_dotenv()
     ```

---

## ▶️ Usage

Run the application:
```bash
streamlit run app.py
```

### Steps:
1. **Upload PDF**: Drag and drop your PDF into the uploader.
2. **Extract & Generate**: Let the app process the PDF, extract text, and generate the mindmap.
3. **Visualize & Download**:
   - View the mindmap interactively.
   - Switch to the markdown tab to view the markdown structure.
   - Download the markdown file for offline use.
