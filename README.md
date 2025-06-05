📰 About the Project
LLM News-to-Instagram Generator is a smart content automation tool that transforms public news articles into shareable content using local large language models (LLMs). It fetches news using a stealthy Selenium-based scraper, summarizes it with a senior editor-style prompt, and generates 2–3 sentence Instagram captions enriched with emojis and hashtags.

This project is ideal for content creators, social media managers, or researchers exploring LLM-based summarization and generation workflows.

🚀 Key Features
Stealthy Web Scraper: Handles popups, ads, and cookie banners using undetected_chromedriver.

Dual Output: Generates both a balanced summary and a catchy Instagram caption per article.

LLM Flexibility: Compare multiple Ollama-supported models (LLaMA 3, Gemma, DeepSeek, etc.) in parallel.

Custom Voice: Drop in your own soft_prompt.txt to tailor the output tone (e.g., news anchor or lifestyle blogger).

Live Progress Bars: See real-time model outputs using threaded execution and Jupyter widgets.

🛠 Tech Stack
Python 3.8+

Jupyter Notebook

Selenium + BeautifulSoup

Ollama (local LLM API)

ipywidgets

ThreadPoolExecutor

Let me know if you'd like me to write the rest of the README structure (e.g., Installation, Usage, Demo, Contributing).
