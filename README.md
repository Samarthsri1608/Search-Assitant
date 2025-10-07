# 🔍 AI Search Assistant

An **AI-powered search assistant** that answers user queries by fetching relevant websites, scraping their content, and summarizing the information using **Gemini’s LLM**.  
It provides concise, factual answers along with the list of sources used — a transparent and intelligent alternative to traditional web searches.

---

## 🚀 Features
- 🌐 Fetches top relevant websites using DuckDuckGo search API  
- 🧠 Summarizes web content using Gemini’s large language models  
- 📚 Displays cited sources for transparency  
- 💬 Interactive CLI interface for custom queries  
- ⚙️ Modular codebase — easy to expand into a web app or API  

---

## 🧩 Tech Stack
- **Python 3.10+**  
- **Gemini API** – for LLM-based summarization  
- **DDGS (DuckDuckGo Search)** – for web search  
- **Requests + BeautifulSoup** – for web scraping  

---

## 🧠 How It Works
1. User enters a question.  
2. The app fetches the top search results from DuckDuckGo.  
3. Each website is scraped and cleaned using BeautifulSoup.  
4. The combined content is summarized by Gemini’s model.  
5. The AI answer and source URLs are displayed to the user.  

---

## 🛠️ Installation

```bash
# Clone the repository
git clone <change>
cd ai-search-assistant

# Install dependencies
pip install -r requirements.txt

Create a .env file in the project root:
GOOGLE_API_KEY=your_api_key_here
```
## Usage

Open Search_Assitant.ipynb in jupyter notbook
Enter your query when prompted, and it will generate a summary of top 10 website data

## Future Improvements

Convert CLI version to a Streamlit web app

Add semantic ranking and filtering

Integrate multiple search APIs

Implement RAG pipeline for contextual accuracy

## Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.
