# Artificial Intelligence (AI) simple Retrieval-Augmented Generation (RAG)

This is a simple Artificial Intelligence (AI) Retrieval-Augmented Generation (RAG) example in just a few lines of Python program code.

You can ask questions about one or multiple text documents from your "data" folder.

It uses Meta's (Facebook's) "FAISS" (Facebook AI Similarity Search) library.

This project works with the [Mistral Instruct (7B)](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1) open source Large Language Model (LLM). This LLM is small enough to be used on a private computers.

You need a Lamini API key for this project. [Get your free API key here](https://app.lamini.ai/). Insert your Lamini API key in the "rag.py" file.

This project works using CPU only and does not require a Graphics Processing Unit (GPU). It is therefore slower, but runs on any computer. It already contains a Python Wheel for Microsoft Windows and Python version 3.11.

If required, you can download [Wheels for other operating systems and Python versions](https://github.com/kyamagu/faiss-wheels), or you can build you own Python Wheel.
