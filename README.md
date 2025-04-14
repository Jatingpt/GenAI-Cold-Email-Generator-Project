# 🔍 GenAI-Powered Job Matching & Cold Email Automation
This project automates the process of identifying relevant job opportunities, matching them with a tech portfolio, and generating personalized cold outreach emails — all powered by Generative AI.

💡 Key Features
Web Scraping: Scrapes job descriptions from company career pages using WebBaseLoader.

LLM-based Information Extraction: Uses LLM (Groq's LLaMA3-70B) to extract role, skills, experience, and job summary in structured JSON format.

Portfolio Matching with Vector Search: Indexes tech portfolios using ChromaDB, and performs semantic search to find the most relevant projects based on required skills.

Personalized Email Generation: Automatically drafts tailored business emails for each job post, using selected portfolio links and company context via LLM prompt engineering.

⚙️ Tech Stack
LLM: Groq + LLaMA3-70B

LangChain: Prompting & chaining logic

ChromaDB: Vector storage & semantic search

Python: Core scripting and orchestration

Pandas: Portfolio data handling
