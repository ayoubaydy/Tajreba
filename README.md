# Tajruba

**Tajruba** is a professional **book and document translation tool** powered by **local large language models (LLMs)** through [Ollama](https://ollama.ai).  
It enables accurate, refined English-to-Arabic translation for books, e-books, and documents — **securely, privately, and offline**.

---

## 🌍 Inspiration

The idea for **Tajreba** was born from the widening gap in **modern Arabic translations**.  
Many of today’s **scientific, literary, and cultural works** from the West either never reach Arabic readers or take years to do so — often due to **publishing restrictions**, **licensing barriers**, or **limited translation initiatives** across the Arab world.  

**Tajruba** was created to help **bridge that gap**, giving individuals, researchers, and readers direct access to global knowledge in their native language — **freely, locally, and instantly**.

---

## 🎥 Watch Tajreba in Action

Check out our official YouTube channel for demos, updates, and translation showcases:  
▶️ [@Tajrebah on YouTube](https://www.youtube.com/@Tajrebah)

---

## ⚙️ How It Works

1. **Download Ollama**  
   Install [Ollama](https://ollama.ai) to run language models locally on your machine.  

2. **Choose Your Arabic Model**  
   We recommend using **`CohereLabs/c4ai-command-r7b`** for high-quality and up-to-date Arabic translations (tested and verified for accuracy).  
   If you test other models and find better results, feel free to **contribute your findings** to improve Tajruba’s recommendations.

3. **Translate Your Book or Document**  
   Import your English e-book or document into **Tajruba**, select your preferred **LLM model**, and start the translation process.  
   Watch as your text is **translated live** into polished, publication-ready Arabic — fully offline.

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

💡 Why Tajreba?

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
