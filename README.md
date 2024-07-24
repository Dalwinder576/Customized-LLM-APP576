---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
The code creates an interactive chat application using Gradio and HuggingFace's Inference API to discuss nutrition. The MyApp class processes a PDF on nutrition, extracts text, and builds a searchable vector database using SentenceTransformers and FAISS. When users ask questions, the app retrieves relevant document excerpts to enhance responses. The respond function integrates these excerpts into contextually relevant answers, guided by a predefined system message about the impact of nutrition on mental and physical well-being. The Gradio interface, configured with example queries and a title, facilitates user interaction, allowing users to learn about the effects and importance of nutrition based on the PDF content.
