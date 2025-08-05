# 🤖 Portfólio de Projetos de Inteligência Artificial

Bem-vindo ao meu portfólio de projetos de Inteligência Artificial! Aqui, você encontrará uma coleção de trabalhos que exploram diferentes aspectos e aplicações de Large Language Models (LLMs), com foco em soluções práticas e arquiteturas limpas.

Cada projeto abaixo é um exemplo de como é possível construir aplicações robustas, privadas e eficientes utilizando ferramentas modernas como **LangChain**, **LM Studio** e **ChromaDB**, com ênfase na execução de modelos de IA localmente.

---

### 📚 Projetos

#### 1. Teacher English: Assistente de IA para Gramática e Vocabulário

Um assistente de ensino de inglês desenvolvido com um serviço RESTful em **Flask**. Este projeto utiliza um LLM rodando localmente (via LM Studio) para oferecer feedback instantâneo sobre gramática, correções e tradução de palavras com exemplos contextuais. É uma solução autônoma e eficiente, ideal para estudantes e professores que buscam uma ferramenta de aprendizado interativa sem depender de serviços em nuvem.

- **Tecnologias:** Flask, LLM Local (LM Studio), Python.
- **Funcionalidades:** Avaliação gramatical, tradução com contexto e verificação de status do LLM.
- **🔗 [Teacher English](https://github.com/EmmanoelMonteiro/teacher-english-ia)**

---

#### 2. Paper-Pal-RAG: Assistente de Leitura para Artigos Científicos

Este projeto é um assistente de leitura inteligente em Python que utiliza a arquitetura **Retrieval Augmented Generation (RAG)** para extrair e sintetizar informações de documentos. Com **LangChain** para orquestração e **ChromaDB** para armazenamento vetorial, ele permite que você faça perguntas sobre o conteúdo de artigos científicos (PDFs e TXTs) de forma eficiente. O LLM também é executado localmente, garantindo privacidade e controle total sobre os dados.

- **Tecnologias:** LangChain, LLM Local (LM Studio), ChromaDB, Python.
- **Funcionalidades:** Ingestão flexível de documentos, RAG, interface de chat por linha de comando.
- **🔗 [Paper-Pal-RAG](https://github.com/EmmanoelMonteiro/paper-pal-rag)**

---

#### 3. basic-chatbot-langchain-ia: Chatbot Básico com LLM Local e CI

Um projeto que demonstra a construção de um chatbot interativo via terminal, utilizando **LangChain** para gerenciar a conversa e um LLM local configurado via **LM Studio**. Além de ser uma excelente introdução ao desenvolvimento de aplicações com LLMs locais, este projeto destaca a importância de práticas de desenvolvimento modernas, como a automação de testes e a integração contínua (CI) com **GitHub Actions**.

- **Tecnologias:** LangChain, LLM Local (LM Studio), Python.
- **Funcionalidades:** Chatbot interativo, testes automatizados, pipeline de CI para linting e validação.
- **🔗 [basic-chatbot-langchain-ia](https://github.com/EmmanoelMonteiro/basic-chatbot-langchain-ia)**

---

Fique à vontade para explorar os repositórios individuais para detalhes técnicos, instruções de execução e exemplos de uso.
