# AI Research Proposal RAG Assistant

This project demonstrates how Retrieval-Augmented Generation (RAG) and LLM-based evaluation can support research proposal automation.

The workflow analyzes a funding opportunity, extracts the core research topic, retrieves relevant research papers, generates proposal ideas, drafts a structured proposal, evaluates the proposal against funding criteria, and applies an improvement loop using LLM-as-Judge feedback.

## Result

This project was completed as part of an Applied Generative AI certification and received a final score of **40 / 40**.

Evaluator feedback highlighted correct LLM setup, clear prompting, strong relevance assessment, coherent proposal ideation, structured proposal generation, systematic evaluation, and meaningful summary recommendations.

## Business Problem

Research teams often spend significant time reviewing funding opportunities, searching prior work, identifying relevant papers, drafting proposal ideas, and aligning proposals with evaluation criteria.

This project explores how generative AI can reduce manual effort and improve consistency by combining:

- Document processing
- Semantic search
- Retrieval-Augmented Generation
- Prompt engineering
- LLM-based evaluation
- Iterative proposal refinement

## Key Capabilities

- Funding opportunity topic extraction
- Research paper ingestion and processing
- Embedding generation
- FAISS vector search
- Research paper relevance assessment
- Proposal idea generation
- Structured research proposal drafting
- Proposal evaluation against criteria
- Revision loop based on evaluator feedback
- Final summary and recommendations

## Workflow

1. Load funding opportunity document.
2. Extract the core research topic.
3. Load and process research papers.
4. Generate embeddings.
5. Store vectors in FAISS.
6. Retrieve relevant papers.
7. Summarize and assess relevance.
8. Generate proposal ideas.
9. Select the strongest idea.
10. Draft a structured research proposal.
11. Evaluate the proposal using LLM-as-Judge.
12. Revise and improve the final proposal.
13. Generate summary and recommendations.

## Selected Proposal Idea

The final selected idea was:

**Leveraging Social Media Dynamics for Personalized Digital Mental Health Interventions Among Young Adults**

This idea was selected because it was strongly aligned with the funding topic and grounded in relevant research related to social media behavior and mental health outcomes.

## Technologies Used

- Python
- Google Colab
- LangChain
- OpenAI-compatible LLM API
- FAISS
- HuggingFace embeddings
- PyPDF
- Pandas
- Prompt engineering
- LLM-as-Judge evaluation

## Repository Structure

- `notebooks/`: sanitized notebook version of the project.
- `docs/`: project documentation, methodology, architecture, and evaluation summary.
- `outputs/`: final HTML report and sample generated proposal.
- `prompts/`: sanitized prompt templates used in the workflow.
- `assets/`: images or visual evidence related to the project.

## Responsible AI and Data Handling

This repository contains a sanitized educational and portfolio version of the project.

It does **not** include:

- API keys
- Tokens
- `config.json`
- Proprietary course files
- Copyrighted research papers
- Private datasets
- Original funding documents or templates unless publicly shareable

The goal is to demonstrate the architecture, workflow, prompting strategy, and evaluation design without redistributing restricted materials.

## What I Learned

This project reinforced the importance of:

- Designing clear prompts with measurable outputs
- Structuring RAG workflows around business objectives
- Validating model outputs against explicit criteria
- Combining retrieval, generation, and evaluation
- Applying human-in-the-loop thinking to AI-assisted workflows

## Potential Improvements

Future versions could include:

- Hybrid search with keyword and vector retrieval
- Metadata-aware retrieval
- Automated citation extraction
- Better source grounding
- Multi-step proposal revision loops
- Human expert review checkpoints
- Streamlit or FastAPI interface for interactive use

## Responsible Use Disclaimer

This repository is intended for educational and portfolio purposes. It demonstrates a technical workflow for AI-assisted research proposal automation and should not be used as a substitute for expert scientific, legal, ethical, or grant-writing review.
