# 📚 Book Recommendation System

A project demonstrating how Large Language Models (LLMs) and vector search can power intelligent book recommendations.

---

##  Project Components

- **Cleaned** text data: `data-exploration.ipynb`  
- **Built** a vector database for semantic search: `vector-search.ipynb`  
- **Classified** books as fiction or non-fiction using zero-shot LLMs: `text-classification.ipynb`  
- **Analyzed** sentiment and extracted emotions with LLMs: `sentiment-analysis.ipynb`  
- **Created** a Gradio web app for book recommendations: `gradio-dashboard.py`  

---

##  Features

-  **Semantic Search**: find books similar to natural language queries (e.g., *"a book about a person seeking revenge"*)  
-  **Classification**: filter books by fiction or non-fiction  
-  **Sentiment Analysis**: sort books by tone (suspenseful, joyful, sad, etc.)  
-  **Web Dashboard**: explore and interact with recommendations through a Gradio app  

---

##  Getting Started

1. **Clone the repository**  
   ```bash
   git clone <repo-url>
   cd <repo-name>

2. **Install dependencies**
```
pip install -r requirements.txt
```

3. **Run the Gradio app**
```
python gradio-dashboard.py
```


🤗 **Hugging Face Demo**

You can try the live demo here:
👉 Hugging Face Spaces - Book Recommender
https://huggingface.co/spaces/Lyonsaldanha/semantic-book-recommender
