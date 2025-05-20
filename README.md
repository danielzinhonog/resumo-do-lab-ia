# 🧠 Laboratório de IA com Azure Speech Studio, Language Studio, Document Intelligence e OpenAI

Este repositório foi criado como parte dos laboratórios práticos propostos no curso da DIO, com o objetivo de aplicar e aprofundar os conhecimentos adquiridos sobre Inteligência Artificial (IA), Processamento de Linguagem Natural, Análise de Fala, Mineração de Conhecimento e IA Generativa utilizando ferramentas da Microsoft Azure.

---

## 🎯 Objetivos

- Aplicar os conceitos fundamentais de IA em ambientes práticos;
- Utilizar ferramentas como Azure Speech Studio, Language Studio, Document Intelligence e Azure OpenAI;
- Documentar as etapas técnicas com clareza e estrutura;
- Utilizar o GitHub como ferramenta para organização e compartilhamento de conhecimento técnico.

---

## 🤖 O que é Inteligência Artificial?

A Inteligência Artificial é a capacidade de sistemas computacionais realizarem tarefas que normalmente exigiriam inteligência humana. Entre suas aplicações estão:

- Previsão de resultados e reconhecimento de padrões;
- Extração de informações de fontes de dados para geração de conhecimento;
- Compreensão da linguagem e participação em conversas;
- Reconhecimento de eventos anormais e tomada de decisão;
- Interpretação de informações visuais.

---

## 🧩 Cargas de Trabalho Comuns de IA

- **Machine Learning**: Criação de modelos preditivos baseados em dados e estatísticas;
- **Visão Computacional**: Interpretação visual por meio de câmeras, vídeos e imagens;
- **Processamento de Linguagem Natural (PLN)**: Interpretação e geração de linguagem falada e escrita;
- **Inteligência de Documentos**: Processamento automatizado de documentos e formulários;
- **Mineração de Conhecimento**: Extração de informações de grandes volumes de dados não estruturados;
- **IA Generativa**: Geração de conteúdo original (texto, imagem, código etc).

---

## ⚖️ Princípios de IA Responsável

- **Imparcialidade**: Prevenir e mitigar preconceitos nos dados;
- **Confiabilidade e Segurança**: Garantir o funcionamento correto e seguro;
- **Privacidade e Segurança**: Proteger dados pessoais e sensíveis;
- **Inclusão**: Desenvolver soluções acessíveis para todos;
- **Transparência**: Tornar os processos compreensíveis para os usuários;
- **Responsabilidade**: Definir quem responde pelas decisões da IA.

---

## 🛠️ Relato da Experiência Prática

Durante os laboratórios, desenvolvi ambientes práticos com os seguintes serviços da Azure:

### 🔊 Speech Studio

- Criação de modelos de conversão de texto em fala (Text-to-Speech) e fala em texto (Speech-to-Text);
- Ajuste de entonação, pausas e pronúncia;
- Gravações com diferentes vozes e sotaques.

### 💬 Language Studio

- Análise de sentimentos;
- Detecção de entidades nomeadas (NER);
- Identificação de informações pessoais (PII);
- Tradução automática e detecção de idioma;
- Respostas a perguntas com base em documentos.

### 📄 Document Intelligence e Mineração de Conhecimento

- Uso do Azure Document Intelligence para análise de formulários PDF digitalizados;
- Treinamento de modelos personalizados com amostras de documentos;
- Uso de modelos pré-treinados para faturas, recibos, e identidades;
- Exploração da Azure Cognitive Search para ingestão de dados, enriquecimento com IA e criação de índices pesquisáveis;
- Aplicação de conjuntos de habilidades cognitivas para identificar entidades, traduzir textos e avaliar sentimentos.

---

## 🗂️ Mineração de Conhecimento e Inteligência de Documentos

### 🧾 Azure Document Intelligence

**Serviços oferecidos:**

- Análise de documentos estruturados e extração de regiões de interesse;
- Treinamento de modelos personalizados com ao menos cinco amostras;
- Reconhecimento semântico de campos em formulários (não apenas OCR).

**Uso do Estúdio de Inteligência de Documentos:**

- Interface no-code para testar modelos e explorar resultados;
- Integração com recursos de IA do Azure.

### 🔍 Azure Cognitive Search

**Etapas do pipeline de mineração de conhecimento:**

- **Ingestão de dados**: Fontes como Azure Blob Storage, Data Lake ou Table Storage;
- **Enriquecimento com IA**: Aplicação de habilidades cognitivas para traduzir, extrair entidades e sentimentos;
- **Criação e Exploração de Índices**: Indexação de conteúdo enriquecido, pesquisa interativa e visualização com dashboards.

---

## 🧠 IA Generativa, Copilotos e Azure OpenAI

### 📌 O que é IA Generativa?

- A IA generativa cria conteúdo original, como texto, imagens ou código, a partir de entradas em linguagem natural.
- Utiliza **modelos de linguagem grandes (LLMs)** para executar tarefas de linguagem, resumo, comparação semântica e criação de novos conteúdos.

### 📚 Modelos de Linguagem Grandes (LLMs)

- Baseados na arquitetura **transformer**, composta por codificadores (entendimento) e decodificadores (geração);
- Trabalham com **tokenização**, **inserções vetoriais** e **mecanismos de atenção** para prever e gerar sequências de texto.

### 🧑‍💼 Copilotos

- Aplicações integradas a sistemas existentes que utilizam IA generativa para ajudar usuários em tarefas específicas;
- Auxiliam na produtividade e criatividade por meio da geração de conteúdos contextuais.

### 🎯 Engenharia de Prompt

Técnicas para melhorar a qualidade das respostas da IA generativa:

- **Linguagem direta**: Ser claro sobre o que se espera ("Liste 10 atrações em Edimburgo...");
- **Mensagens do sistema**: Definir o comportamento esperado do assistente ("Você é um bot amigável...");
- **Exemplos**: Aprendizado com poucas demonstrações ("Visite o castelo pela manhã...");
- **Contexto/Dados básicos**: Fornecer dados como e-mails, textos ou instruções para fundamentar a resposta.

### ☁️ Azure OpenAI

- Plataforma que hospeda modelos como **GPT-4**, **GPT-3.5**, **DALL·E** e **modelos de incorporação**;
- Oferece:
  - Segurança empresarial com RBAC e redes privadas;
  - Ferramentas para mitigar uso indevido;
  - Interfaces como Azure OpenAI Studio, SDKs, API REST e CLI.

### 🖼️ Geração de Imagens com DALL·E

- **Criação** de imagens a partir de prompts em linguagem natural;
- **Edição** de imagens, incluindo adição/remoção de elementos e mudança de estilo;
- **Variações** com base em uma imagem enviada pelo usuário.

---

## ✅ Resultados Atingidos

- Todos os desafios práticos do curso foram aplicados em ambientes reais do Azure;
- Os conceitos de IA tradicional, PLN, mineração de conhecimento e IA generativa foram integrados;
- Os serviços explorados foram documentados com clareza e organizados neste repositório;
- O uso do GitHub consolida um portfólio técnico acessível e reutilizável.

---

## 🔗 Referências

- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.azure.com/)
- [Azure Document Intelligence](https://learn.microsoft.com/pt-br/azure/ai-services/document-intelligence/)
- [Azure Cognitive Search](https://learn.microsoft.com/pt-br/azure/search/)
- [Azure OpenAI Service](https://learn.microsoft.com/pt-br/azure/cognitive-services/openai/)
- [Documentação Microsoft AI](https://learn.microsoft.com/pt-br/azure/cognitive-services/)
