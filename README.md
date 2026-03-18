# HealthLLM – AI-Based Healthcare Assistant

An LLM-powered symptom-to-condition classifier that generates contextually grounded medical summaries using Retrieval-Augmented Generation (RAG).

## What it does
- Classifies symptoms across 10+ disease categories
- Retrieves relevant medical context using sentence-transformer embeddings
- Generates safe, grounded responses via Qwen 1.5 LLM + few-shot prompting
- Designed with ethical AI constraints for healthcare-sensitive queries

## Tech Stack
- **LLM:** Qwen 1.5
- **Retrieval:** Sentence-Transformers (RAG pipeline)
- **Prompting:** Few-shot prompting, Chain-of-Thought
- **Language:** Python

## How to Run
1. Clone the repo: `git clone https://github.com/PrajwalRaj17/HealthLLM`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `HealthLLM.ipynb` in Jupyter Notebook or Google Colab
   
