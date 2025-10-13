# Tajruba

**Tajruba** is a professional **book and document translation tool** powered by **local large language models (LLMs)** through [Ollama](https://ollama.ai).  
It enables accurate, refined English-to-Arabic translation for books, e-books, and documents — **securely, privately, and offline**.

---

## 🌍 Inspiration

The idea for **Tajruba** was born from a growing gap in **modern Arabic translations**.  
Many of the latest **scientific, literary, and cultural works** in the West never reach Arabic readers — often due to **publishing restrictions** or **limited translation rights** in the Arab world.  

Tajruba aims to **bridge that gap**, empowering individuals, researchers, and readers to access global knowledge in their native language — **freely and locally**.

---

## ✨ Features

- **Multi-Format Input** — Translate DOCX, PDF, EPUB, TXT, and HTML files seamlessly.  
- **Local Translation Engine** — Uses Ollama-based local LLMs for private, cost-free translation.  
- **Real-Time Progress** — Streamed translation with live updates and chunk-by-chunk output.  
- **Customizable Prompts** — Adjust tone, precision, and translation style through editable prompts.  
- **Modern Interface** — Built with Gradio; features dark mode, live preview, and progress tracking.  
- **DOCX Export** — Save your Arabic translation in a polished, editable Word document.

---

## ⚙️ Getting Started

### **Requirements**
- Python 3.8 or higher  
- [Ollama](https://ollama.ai) installed locally  
- (Optional) Additional parsers for enhanced file handling:
  ```bash
  pip install pymupdf pdfminer.six beautifulsoup4 ebooklib
Installation
git clone https://github.com/ayoubaydy/tajruba.git
cd tajruba
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

Run the Translator
python app.py


Then open your browser and visit:
👉 http://127.0.0.1:7860

💡 Why Tajruba?

Because access to knowledge shouldn’t be bound by geography or publishing limitations.
Tajruba is a step toward a more inclusive Arabic digital library, enabling independent translators and curious minds to bring the world’s newest ideas home — in their own language.

🤝 Contributing

Contributions are welcome!
Please see CONTRIBUTING.md
 for details on how to submit issues or pull requests.

📜 License

Distributed under the MIT License.
See LICENSE
 for more information.

Tajruba — Translating knowledge, preserving meaning. Locally.

---

Would you like me to add a short **tagline + badges section** (like “Built with Python • Powered by Ollama • MIT License”) at the top for a more polished GitHub appearance?
