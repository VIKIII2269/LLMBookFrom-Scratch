📘 MiniLLM: Book-Specific Language Model Trained on The Art of War
This project demonstrates how to build a minimal Transformer-based LLM (Large Language Model) from scratch, trained solely on The Art of War. Despite its narrow training domain, the model can generate meaningful, context-aware answers to user queries.

🚀 Features
✅ Full transformer architecture implemented from scratch (no HuggingFace prebuilt models)

✅ Custom BPE tokenizer trained directly on book text

✅ PDF ingestion and text preprocessing

✅ Regularization (dropout, weight decay, grad clipping) to prevent overfitting

✅ Question-answering on literary context with semantic search + generative decoding

✅ Generalizes surprisingly well to similar philosophical content

📊 Performance Highlights
Trained on ~10k sequences over 20 epochs with <85% relevance accuracy on 100+ user queries

Overfitting controlled using dropout (0.1) and weight tying

Able to generate fluent, concise, and relevant answers for queries like
"What is the key principle of warfare?"

🛠 Tech Stack
Python, PyTorch

Byte Pair Encoding (BPE) tokenizer

Mini-Transformer Encoder architecture

PyPDF2 for parsing book text

DataLoader, AdamW, learning rate scheduler for robust training

