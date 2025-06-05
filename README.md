## 🧠 About the LLM News-to-Instagram Generator

The **LLM News-to-Instagram Generator** is a streamlined, intelligent pipeline designed to automate content creation from public news articles. It integrates advanced web scraping with local large language models (LLMs) to generate both editorial-style summaries and engaging Instagram captions. This system is ideal for social media managers, journalists, and content creators looking to convert real-time news into platform-ready posts with minimal effort.

Built with flexibility and performance in mind, the pipeline supports multiple model backends via Ollama, customizable tone settings, and real-time multi-model comparison—offering both creative freedom and operational efficiency.

---

## 🔑 Key Features

- **Dual Output Generation**: Produces both a balanced news summary and an Instagram-friendly caption from any public article.
- **Stealth Web Scraper**: Uses undetected Selenium with dynamic fallback to handle overlays, modals, and cookie banners.
- **Parallel Model Execution**: Compares multiple local LLMs (LLaMA, Gemma, DeepSeek, etc.) side-by-side using threaded execution.
- **Customizable Prompting**: Allows tone and voice adjustment through a soft prompt file (`soft_prompt.txt`).
- **Interactive Jupyter UI**: Empowers users to select models, tweak generation parameters, and preview outputs in real time.

---

## 🛠 Tech Stack

- **Python 3.8+** – Core logic and orchestration  
- **Ollama** – Local LLM hosting and model management  
- **undetected-chromedriver + Selenium** – Robust, stealthy web scraping  
- **BeautifulSoup** – HTML parsing and content extraction  
- **ipywidgets** – Interactive controls within Jupyter Notebook  
- **ThreadPoolExecutor** – Parallel model processing  
