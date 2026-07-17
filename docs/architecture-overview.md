# Architecture Overview

The architecture follows this sequence:

1. Funding opportunity document ingestion
2. Topic extraction using an LLM
3. Research paper corpus ingestion
4. PDF loading and text extraction
5. Text chunking
6. Embedding generation
7. FAISS vector indexing
8. Semantic retrieval
9. Paper summarization
10. Proposal idea generation
11. Proposal drafting
12. LLM-as-Judge evaluation
13. Proposal revision
14. Final summary and recommendations

This design combines retrieval, generation, and evaluation to support research proposal automation.
