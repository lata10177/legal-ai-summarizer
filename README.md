# legal-ai-summarizer
An automated legal document summarizer built with Hugging Face and BART.

# Project Goal
To build an automated Legal Document Summarizer that can take long, complex US Congressional and California state bills and condense them into short, readable summaries.

# The Tech Stack (What you used)
Platform: Google Colab (using T4 GPU acceleration).
Library: Hugging Face transformers and datasets.
Model: facebook/bart-large-cnn (A 400M+ parameter deep learning model).
Dataset: billsum (Professional legal corpus).


 # * Legal Document Summarizer | Python, Hugging Face, BART *
Developed an automated NLP tool to condense complex US Congressional bills into 3-sentence summaries using the BART-large-cnn model.
Managed tokenization and truncation for long legal texts, ensuring 100% processing reliability on a T4 GPU.
Implemented manual inference with custom beam search (num_beams=4) to bypass library constraints and improve summary accuracy.



note :
 Hugging Face is the "GitHub of AI." It is the world’s largest platform where researchers and companies share pre-trained models (like BART), massive datasets (like BillSum), and the software tools (Transformers library) to run them. BART (Bidirectional and Auto-Regressive Transformers) is a specific type of AI model created by Meta (Facebook).
