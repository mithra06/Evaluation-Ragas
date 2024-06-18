🔍 Understanding RAG: RAG integrates the power of retrieval models with generative models to enhance the quality and relevance of generated text. By leveraging external knowledge from retrieved documents, RAG significantly improves content coherence and factual accuracy.


🎶 Introducing Ragas: In our recent research, we explored the concept of using Ragas—a novel approach inspired by classical Indian music scales—to evaluate RAG models. Ragas is a framework that helps you evaluate your Retrieval Augmented Generation (RAG) pipelines.


Here you can see that we are using 4 metrics, 

faithfulness - It is calculated from answer and retrieved context.

context_precision - calculated based on both the question and contexts

answer_relevancy - a measure of how relevant the answer is to the question

context_recall: It is computed based on the ground truth and the retrieved context, and the values range between 0 and 1, with higher values indicating better performance.
