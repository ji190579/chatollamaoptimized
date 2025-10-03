Arxiv RAG Bot – Enhanced Version

This project is based on the original notebook:
Hadi-Kassem/Arxiv-RAG-bot

I’ve added several enhancements to make it run significantly faster on my local machine (Windows, 16 GB RAM, Intel Core i7).
Response time is now 10–15 seconds, compared to the original ~2 minutes.

Key Improvements

Switched Models

Replaced Mistral with LLaMA for better performance on CPU.

Fine-Tuned Parameters

Adjusted temperature and num_predict for faster and more relevant responses.

Smart Context Handling

Added summarization for long contexts to keep responses concise and efficient.

Prompt Engineering

Improved prompts to increase accuracy and reduce unnecessary output.
