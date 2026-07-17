# AI Research Proposal RAG Assistant

This project demonstrates how Retrieval-Augmented Generation (RAG) and LLM-based evaluation can support research proposal automation.

The workflow analyzes a funding opportunity, extracts the core research topic, retrieves relevant research papers, generates proposal ideas, drafts a structured proposal, evaluates the proposal against funding criteria, and applies an improvement loop using LLM-as-Judge feedback.

## Best way to review this repository

Start with the README to understand the academic context, project result, RAG workflow, and evaluation approach.

Then review the repository in this order:

- Project objective and academic context
- RAG workflow and document retrieval approach
- LangChain, FAISS, embeddings, and LLM setup notes
- Research proposal generation flow
- LLM-as-Judge evaluation approach
- Final result and evaluator feedback

This repository is best reviewed as an applied AI workflow for research proposal support, source-grounded drafting, structured ideation, and systematic evaluation.

The public version has been reviewed and sanitized for portfolio visibility. It does not include private course materials, proprietary content, credentials, API keys, or sensitive data.

## Result

This project was developed as part of the Applied Generative AI certification program from Johns Hopkins University and received a final score of **40 / 40**.

Evaluator feedback highlighted correct LLM setup, clear prompting, strong relevance assessment, coherent proposal ideation, structured proposal generation, systematic evaluation, and meaningful summary recommendations.

## Business Problem

Research teams often spend significant time reviewing funding opportunities, searching prior work, identifying relevant papers, drafting proposal ideas, and aligning proposals with evaluation criteria.

This project explores how generative AI can reduce manual effort and improve consistency by combining document processing, semantic search, Retrieval-Augmented Generation, prompt engineering, LLM-based evaluation, and iterative proposal refinement.

## Project Objective

The objective of this project is to demonstrate a complete AI-assisted workflow that can:

- Analyze a funding opportunity document.
- Identify the core research topic.
- Retrieve relevant research papers from a document corpus.
- Generate proposal ideas based on filtered research.
- Draft a structured research proposal.
- Evaluate the proposal against defined review criteria.
- Improve the proposal through an LLM-based revision loop.

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

1. Load the funding opportunity document.
2. Extract the core research topic.
3. Load and process research papers.
4. Split documents into chunks.
5. Generate embeddings.
6. Store vectors in FAISS.
7. Retrieve relevant papers using semantic search.
8. Summarize and assess paper relevance.
9. Generate proposal ideas based on filtered research.
10. Select the strongest proposal idea.
11. Draft a structured research proposal.
12. Evaluate the proposal using LLM-as-Judge.
13. Revise and improve the final proposal.
14. Generate summary and recommendations.

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

## Project Files

- `notebooks/rag_research_proposal_automation.ipynb`: editable notebook containing the implementation workflow.
- `outputs/final_project_report.html`: exported HTML version of the executed notebook, included as a readable project report.
- `outputs/sample_generated_proposal.md`: sanitized sample of the generated proposal output.

## Documentation

Additional documentation is available in the `docs/` folder:

- `docs/project-overview.md`: high-level overview of the project.
- `docs/methodology.md`: explanation of the RAG workflow and project methodology.
- `docs/architecture-overview.md`: architecture sequence and workflow components.
- `docs/evaluation-summary.md`: summary of the final evaluation result.

## Prompt Templates

The `prompts/` folder includes sanitized versions of the main prompt strategies used in the workflow:

- Topic extraction
- Research paper relevance assessment
- Proposal ideation
- Proposal generation
- Proposal evaluation

These prompt templates are included to demonstrate the prompting strategy without redistributing proprietary course materials or private data.

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

- Designing clear prompts with measurable outputs.
- Structuring RAG workflows around business objectives.
- Validating model outputs against explicit criteria.
- Combining retrieval, generation, and evaluation.
- Applying human-in-the-loop thinking to AI-assisted workflows.
- Keeping sensitive files, credentials, and proprietary material out of public repositories.
- Using AI not only to generate content, but also to evaluate and improve it.

## Potential Improvements

Future versions could include:

- Hybrid search with keyword and vector retrieval.
- Metadata-aware retrieval.
- Automated citation extraction.
- Better source grounding.
- Multi-step proposal revision loops.
- Human expert review checkpoints.
- Streamlit or FastAPI interface for interactive use.
- Automated quality scoring dashboards.
- Configurable retrieval filters by topic, year, author, or methodology.
- Integration with a document management system or research knowledge base.

## Portfolio Relevance

This project demonstrates applied capabilities in:

- Generative AI solution design
- Retrieval-Augmented Generation
- Document intelligence
- Semantic search
- Prompt engineering
- AI-assisted decision support
- LLM-based evaluation
- Research automation
- Workflow orchestration
- Responsible AI implementation

## Responsible Use Disclaimer

This repository is intended for educational and portfolio purposes. It demonstrates a technical workflow for AI-assisted research proposal automation and should not be used as a substitute for expert scientific, legal, ethical, clinical, or grant-writing review.

## Author

**Anibal Arias**  
Technology Development Manager | IT Delivery | Applied Generative AI | RAG Workflows
