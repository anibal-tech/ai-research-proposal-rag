# Methodology

The workflow follows a Retrieval-Augmented Generation architecture.

## Steps

1. Load funding opportunity document.
2. Extract the main research topic using an LLM prompt.
3. Load research papers from a PDF corpus.
4. Split documents into chunks.
5. Generate embeddings.
6. Store embeddings in FAISS.
7. Retrieve papers relevant to the topic.
8. Summarize relevant papers.
9. Generate research proposal ideas.
10. Select the strongest proposal idea.
11. Generate a structured research proposal.
12. Evaluate proposal quality using LLM-as-Judge.
13. Revise the proposal based on feedback.
14. Summarize results and recommendations.
