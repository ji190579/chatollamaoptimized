🚀 Arxiv RAG Bot – Enhanced Version

This project is based on the original notebook:
👉 Hadi-Kassem/Arxiv-RAG-bot
https://github.com/Hadi-Kassem/Arxiv-RAG-bot/blob/main/main.ipynb

I’ve added several enhancements to make it run significantly faster on my local machine (Windows, 16 GB RAM, Intel Core i7).
⏱ Response time is now 10–15 seconds, compared to the original ~2 minutes.

🔑 Key Improvements
⚡ Switched Models

Replaced Mistral with LLaMA for better performance on CPU.

🎯 Fine-Tuned Parameters

Adjusted temperature and num_predict for faster and more relevant responses.

📚 Smart Context Handling

Added summarization for long contexts to keep responses concise and efficient.

🧠 Prompt Engineering

Improved prompts to increase accuracy and reduce unnecessary output.

🔮 Future Enhancements

📑 Smart Chunking → Implement intelligent document splitting to improve retrieval accuracy and context management.

💾 Caching → Store and reuse frequent queries to reduce response time even further.

🏋️ Model Fine-Tuning → Train the model on 5,000 question–answer pairs generated from a larger model (e.g., ChatGPT), using Unsloth on Google Colab for efficient fine-tuning.
