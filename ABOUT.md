# Arthur Félix - Experience & Projects

English · [Português (Brasil)](ABOUT.pt-BR.md)

[← Back to my profile](README.md)

**Researcher and Developer at LACINA · Computer Science at UFCG**

I work on applied AI, natural language processing, and information retrieval, from model training and document processing to experimental evaluation. I'm a Computer Science student at the Federal University of Campina Grande (UFCG), based in Campina Grande, Brazil.

[LinkedIn](https://www.linkedin.com/in/arthurfsiqueira/) · [Research paper](https://arxiv.org/abs/2605.11986)

## Experience

At **LACINA**, I contribute to research and development projects connecting AI and software engineering:

- **ANATEL:** developed workflows to classify court decisions and extract structured information from their metadata, supporting jurisprudence retrieval for the agency's legal compliance and risk mitigation. The GPT-4o-mini classification workflow achieved a **macro F1 of 0.77 and 80% accuracy on 119 expert-annotated decisions**. Structured extraction achieved **89.8% field-level accuracy across 500 assessments covering 20 attributes in 25 decisions**, validated by ANATEL legal experts. I also explored thematic clustering of legal issues using extracted topic labels, `intfloat/multilingual-e5-base` embeddings, and HDBSCAN. The clustering implementation is not yet public.
- **Dell (current project):** investigate automated repair of vulnerabilities introduced by third-party dependencies, including agentic approaches and research into remediation techniques.

## Selected projects

### [Legal Citation Verifier](https://github.com/ArthurHappx/verificador-citacoes-juridicas)

An offline pipeline that identifies Brazilian legal citations, extracts their identifiers, retrieves candidates from a reference database, and classifies citations as real, fabricated, or incomplete within that database's coverage. Developed for the Jusbrasil BRACIS 2026 challenge.

**My contribution:** led the team, planned the module boundaries, and trained the BERTimbau NER model to identify citations with exact start and end offsets in the original text. I also explored regex approaches that were later incorporated into the information extraction module.

### [ANATEL Legal Information Pipeline](https://github.com/ArthurHappx/kdd-pado-anatel)

A KDD pipeline for identifying relevant court decisions and structuring legal information for research on ANATEL regulatory proceedings.

**My contribution:** built the classification and structured extraction workflow using court-record metadata, including case summaries, decisions, and court identifiers. This work and the thematic clustering research described above were developed at LACINA.

### [FIA Regulations RAG](https://github.com/ArthurHappx/fia-regulations-rag)

A retrieval-augmented generation pipeline for questions in Portuguese about Formula 1 regulations, comparing three preprocessing strategies with semantic retrieval and cross-encoder reranking.

**My contribution:** collaborated across document preprocessing and RAG implementation. The LLM-as-a-Judge evaluation was developed by other team members.

### [LLM Evaluation for Database Modeling](https://github.com/ArthurHappx/llm-er-modeling)

Research on the limitations of LLMs when transforming natural language requirements into database models, with experimental artifacts and analysis scripts.

**My contribution:** designed the requirements specifications, served as one of three evaluators for scenario 1, and led the writing of the [paper](https://arxiv.org/abs/2605.11986), with revisions from coauthors.

## More work

- [Statistical Learning: College Dataset](https://github.com/ArthurHappx/islr-college-analysis) -- exploratory data analysis and multiple linear regression.

## Programming Languages I've Worked With

Python · Java · C++ · Haskell · Prolog · TypeScript

## Technologies I've Worked With

Hugging Face Transformers · LangChain · LangGraph · pandas · Sentence Transformers · scikit-learn · FAISS · PostgreSQL · SQLite · Docker · Git
