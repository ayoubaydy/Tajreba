# Tajreba

**Tajreba** is a professional **book and document translation tool** powered by **local large language models (LLMs)** through [Ollama](https://ollama.ai).  
It enables accurate, refined English-to-Arabic translation for books, e-books, and documents — **securely, privately, and offline**.

## 🌍 Inspiration

The idea for **Tajreba** was born from the widening gap in **modern Arabic translations**.  
Many of today’s **scientific, literary, and cultural works** from the West either never reach Arabic readers or take years to do so — often due to **publishing restrictions**, **licensing barriers**, or **limited translation initiatives** across the Arab world.  

**Tajreba** was created to help **bridge that gap**, giving individuals, researchers, and readers direct access to global knowledge in their native language — **freely, locally, and instantly**.

## 🎥 Watch Tajreba in Action

Check out our official YouTube channel for demos, updates, and translation showcases:  
▶️ [@Tajrebah on YouTube](https://www.youtube.com/@Tajrebah)

## ⚙️ How It Works

1. **Download Ollama**  
   Install [Ollama](https://ollama.ai) to run language models locally on your machine.  

2. **Choose Your Arabic Model**  
   We recommend using **`CohereLabs/c4ai-command-r7b`** for high-quality and up-to-date Arabic translations (tested and verified for accuracy).  
   If you test other models and find better results, feel free to **contribute your findings** to improve Tajreba’s recommendations.

3. **Translate Your Book or Document**  
   Import your English e-book or document into **Tajreba**, select your preferred **LLM model**, and start the translation process.  
   Watch as your text is **translated live** into polished, publication-ready Arabic — fully offline.

💡 **Tip:**  
For best results, convert your EPUB files to **DOCX** before translation.  
This gives you better control to remove images, citations, or references.  
You can use [Calibre](https://calibre-ebook.com/) — a free, open-source tool for EPUB conversion.

## ✨ Features

- **Multi-Format Input** — Translate DOCX, PDF, EPUB, TXT, and HTML files seamlessly.  
- **Local Translation Engine** — Uses Ollama-based local LLMs for private, cost-free translation.  
- **Real-Time Progress** — Streamed translation with live updates and chunk-by-chunk output.  
- **Customizable Prompts** — Adjust tone, precision, and translation style through editable prompts.  
- **Modern Interface** — Built with Gradio; features dark mode, live preview, and progress tracking.  
- **DOCX Export** — Save your Arabic translation in a polished, editable Word document.

## ⚙️ Getting Started

### Requirements
- Python 3.8 or higher  
- [Ollama](https://ollama.ai) installed locally  
- (Optional) Additional parsers for enhanced file handling:
  ```bash
  pip install pymupdf pdfminer.six beautifulsoup4 ebooklib
Installation
bash
Copy code
git clone https://github.com/ayoubaydy/tajruba.git
cd tajruba
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
Run the Translator
bash
Copy code
python app.py
Then open your browser and visit:
👉 http://127.0.0.1:7860

🗣️ Default Translation Prompt

Tajreba includes a carefully crafted default prompt designed to produce professional, refined Arabic translations suitable for publication:

Default Prompt:

You are a professional English-Arabic translator. Translate the following text from English to Arabic in a refined, sophisticated, and professional book-author style. Ensure that your translation is clear and does not include any notes, disclaimers, or commentary about the original text's quality. Replace numerical figures with their corresponding words in Arabic, including large numbers, decimals, and scientific values. Remove any citation numbers that appear at the end of sentences. Translate all words, including scientific terms. Only provide the translated text.

This default prompt can be edited or replaced to achieve better results for specific writing styles or other target languages.
You can modify it directly within the app interface to fine-tune tone, clarity, or translation fidelity according to your needs.



💡 Why Tajreba?
Because access to knowledge shouldn’t be bound by geography or publishing limitations.
Tajreba is a step toward a more inclusive Arabic digital library, enabling independent translators and curious minds to bring the world’s newest ideas home — in their own language.

🤝 Contributing
Contributions are welcome!
If you test new models, improve translation prompts, or enhance the workflow, please share your findings to help strengthen Tajreba’s mission.

Tajreba — Translating knowledge, preserving meaning. Locally.