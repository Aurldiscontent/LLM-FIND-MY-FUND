Find My Funds is an intelligent mutual fund search engine that helps users find the most relevant mutual funds based on natural language queries like:

"Show me tax-saving funds"
"Tech sector funds with high return"
"Funds with HDFC holdings"

The model uses natural language understanding and semantic search to match user queries with detailed fund descriptions.

🚀 Features
🔍 Smart Search: Understands the meaning behind queries, not just keywords.

🧠 Embeddings with Sentence Transformers: Converts text into vectors for comparison.

⚡ Fast Searching: Uses FAISS (Facebook AI Similarity Search) for quick lookup.

🛠️ Intent Detection: Automatically filters based on user needs like tax-saving, high returns, etc.

💾 Persistent Embeddings: Saves & loads preprocessed data to avoid re-computation.

🧰 Tech Stack
Python

Pandas

SentenceTransformers (for embeddings)

FAISS (for fast nearest-neighbor search)

Scikit-learn

Regex (for keyword-based intent detection)

This is the link to my UI for the same project - 
https://llm-mutual-fund-finder.lovable.app/ -
