# Arthur Félix - Experiência e Projetos

[English](ABOUT.md) · Português (Brasil)

[← Voltar ao meu perfil](README.pt-BR.md)

**Pesquisador e desenvolvedor no LACINA · Ciência da Computação na UFCG**

Trabalho com IA aplicada, processamento de linguagem natural e recuperação de informação, desde o treinamento de modelos e o processamento de documentos até a avaliação experimental. Sou estudante de Ciência da Computação na Universidade Federal de Campina Grande (UFCG) e moro em Campina Grande, Brasil.

[LinkedIn](https://www.linkedin.com/in/arthurfsiqueira/) · [Artigo de pesquisa](https://arxiv.org/abs/2605.11986)

## Experiência

No **LACINA**, contribuo para projetos de pesquisa e desenvolvimento que conectam IA e engenharia de software:

- **ANATEL:** desenvolvi fluxos para classificar decisões judiciais e extrair informações estruturadas de seus metadados, apoiando a recuperação de jurisprudência para a conformidade jurídica e a mitigação de riscos da agência. O workflow de classificação com GPT-4o-mini alcançou **F1 macro de 0,77 e acurácia de 80% em 119 decisões anotadas por especialistas**. A extração estruturada atingiu **89,8% de acerto por campo em 500 avaliações, abrangendo 20 atributos de 25 decisões**, com validação de especialistas jurídicos da ANATEL. Também explorei o clustering temático de questões jurídicas usando algumas das informações estruturadas extraídas, embeddings do modelo `intfloat/multilingual-e5-base` e HDBSCAN. A implementação do clustering ainda não é pública.
- **Dell (projeto atual):** investigo a correção automatizada de vulnerabilidades introduzidas por dependências de terceiros, incluindo abordagens baseadas em agentes e pesquisa sobre técnicas de correção.

## Projetos selecionados

### [Verificador de Citações Jurídicas](https://github.com/ArthurHappx/verificador-citacoes-juridicas)

Um pipeline offline que identifica citações jurídicas brasileiras, extrai seus identificadores, recupera candidatos de uma base de referência e classifica as citações como reais, inventadas ou incompletas, dentro da cobertura dessa base. Desenvolvido para o desafio Jusbrasil BRACIS 2026.

**Minha contribuição:** liderei a equipe, planejei os limites e as responsabilidades dos módulos e treinei o modelo de reconhecimento de entidades nomeadas (NER) BERTimbau para identificar citações com posições exatas de início e fim no texto original. Também explorei abordagens com expressões regulares que foram posteriormente incorporadas ao módulo de extração de informações.

### [Pipeline de Informações Jurídicas da ANATEL](https://github.com/ArthurHappx/kdd-pado-anatel)

Um pipeline de descoberta de conhecimento em bases de dados (KDD) para identificar decisões judiciais relevantes e estruturar informações jurídicas para pesquisas sobre processos regulatórios da ANATEL.

**Minha contribuição:** desenvolvi o fluxo de classificação e extração estruturada usando metadados de registros judiciais, incluindo ementas, decisões e identificadores de tribunais. Esse trabalho e a pesquisa de agrupamento temático descrita acima foram desenvolvidos no LACINA.

### [RAG para Regulamentos da FIA](https://github.com/ArthurHappx/fia-regulations-rag)

Um pipeline de geração aumentada por recuperação (RAG) para perguntas em português sobre os regulamentos da Fórmula 1, comparando três estratégias de pré-processamento com recuperação semântica e reordenação por cross-encoder.

**Minha contribuição:** colaborei no pré-processamento dos documentos e na implementação do RAG. A avaliação com LLM como juiz (LLM-as-a-Judge) foi desenvolvida por outros integrantes da equipe.

### [Avaliação de LLMs para Modelagem de Bancos de Dados](https://github.com/ArthurHappx/llm-er-modeling)

Pesquisa sobre as limitações de LLMs na transformação de requisitos em linguagem natural em modelos de bancos de dados, com artefatos experimentais e scripts de análise.

**Minha contribuição:** elaborei as especificações de requisitos, atuei como um dos três avaliadores do cenário 1 e liderei a escrita do [artigo](https://arxiv.org/abs/2605.11986), com revisões dos coautores.

## Outros trabalhos

- [Aprendizado Estatístico: Conjunto de Dados College](https://github.com/ArthurHappx/islr-college-analysis) -- análise exploratória de dados e regressão linear múltipla.

## Linguagens de programação com que já trabalhei

Python · Java · C++ · Haskell · Prolog · TypeScript

## Tecnologias com que já trabalhei

Hugging Face Transformers · LangChain · LangGraph · pandas · Sentence Transformers · scikit-learn · FAISS · PostgreSQL · SQLite · Docker · Git
