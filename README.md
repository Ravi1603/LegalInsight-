# LegalInsight: Abstractive Text Summarization and Conversational AI for Legal Documents
In this project, we develop LegalInsight, an abstractive summarization model that generates concise summaries of legal documents. These summaries aim to simplify complex legal texts, making them more accessible to a wider audience. The project also includes a Retrieval-Augmented Generation (RAG) based conversational chatbot, which allows users to ask questions about the legal documents and their summaries. The chatbot retrieves relevant sections from the document or summary to provide precise answers, as well as definitions for any unfamiliar legal terms.

To train the text summarizer, we utilize multiple datasets from the Hugging Face library that are relevant to the legal domain, including  ccdv/govreport-summarization, and nhankins/legal\_summary\_data. We fine-tune and evaluate three pre-trained models—BART, T5, and PEGASUS—and compare their performance to select the best model for generating summaries. Evaluation metrics such as ROUGE and BLEU scores are used to assess the quality of the summaries.

For the RAG-based chatbot, we integrate the document retrieval process with the generative model to provide contextual, accurate answers to users' questions. We use theatticusproject/cuad-qa dataset for training the chatbot. The performance of the chatbot is measured using metrics like F1 score and Exact Match (EM) for answer accuracy, as well as user satisfaction through interaction testing. The project will be deployed with a user-friendly interface designed to assist individuals of all age groups in understanding and navigating lengthy legal documents. The goal is to provide a tool that simplifies the reading and interpretation process, making legal information more accessible and easier to comprehend.

This tool will provide a user-friendly platform to help users better understand complex legal texts by offering concise summaries and conversational support for legal queries.




