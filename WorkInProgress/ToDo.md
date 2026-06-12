# TODO.md

# Bellacosa Mainframe Sales Copilot

## Roadmap de Implementação

------

# Objetivo

Transformar a base de conhecimento Bellacosa Mainframe em um Copiloto de Vendas e Atendimento capaz de responder dúvidas, tratar objeções, apoiar vendedores e sugerir oportunidades comerciais.

------

# Visão Geral da Arquitetura

```text
Usuário
   │
   ▼
ChatGPT / Copilot
   │
   ▼
System Prompt
   │
   ▼
Base de Conhecimento
   │
 ┌─┼──────────────────┐
 │ │                  │
 ▼ ▼                  ▼
faq.md        tecnologias.md
objecoes.md   cursos.md
servicos.md
```

------

# Fase 1 - MVP

## Objetivo

Criar um protótipo funcional sem programação.

------

## Passo 1

Criar os arquivos:

```text
knowledge/

faq.md
tecnologias.md
objecoes.md
cursos.md
servicos.md
```

Status:

-  Fazer
-  Revisar
-  Publicar

------

## Passo 2

Criar o system-prompt.md

Objetivo:

Definir:

- Personalidade
- Regras
- Limites
- Comportamento

Status:

-  Fazer
-  Revisar
-  Testar

------

## Passo 3

Criar exemplos de conversa

Arquivo:

```text
exemplos/conversas.md
```

Objetivo:

Simular situações reais.

Status:

-  Fazer
-  Revisar

------

## Passo 4

Testar manualmente no ChatGPT

Prompt:

"Você é o Bellacosa Mainframe Sales Copilot."

Anexar:

- faq.md
- tecnologias.md
- objecoes.md

Executar perguntas.

Exemplos:

- O que é COBOL?
- Vale a pena aprender Mainframe?
- Como integrar Mainframe com APIs?

Status:

-  Fazer

------

# Fase 2 - GPT Personalizado

## Objetivo

Transformar o projeto em um GPT customizado.

------

## Passo 1

Criar GPT no ChatGPT.

Adicionar:

- Nome
- Descrição
- Instruções

------

## Passo 2

Carregar a base de conhecimento.

Upload:

- faq.md
- tecnologias.md
- cursos.md
- servicos.md
- objecoes.md

------

## Passo 3

Executar testes.

Perguntas:

- Técnicas
- Comerciais
- Carreira
- Modernização

------

## Resultado Esperado

O GPT deve responder como um especialista Bellacosa Mainframe.

Status:

-  Fazer

------

# Fase 3 - Aplicação Web

## Objetivo

Criar interface própria.

------

## Tecnologias

Frontend:

- HTML
- CSS
- JavaScript

ou

- React

------

## Backend

- Python
- Flask

ou

- Node.js

------

## Fluxo

```text
Usuário
   │
   ▼
Website
   │
   ▼
API OpenAI
   │
   ▼
Bellacosa Mainframe Copilot
```

------

## Funcionalidades

- Chat
- Histórico
- FAQ
- Sugestões automáticas

Status:

-  Planejar
-  Desenvolver

------

# Fase 4 - RAG

## Objetivo

Evitar alucinações.

------

## Ferramentas

- LangChain
- LlamaIndex
- ChromaDB

------

## Processo

```text
Pergunta
    │
    ▼
Busca na Base
    │
    ▼
Trechos Relevantes
    │
    ▼
IA
    │
    ▼
Resposta
```

------

## Benefícios

- Mais precisão
- Mais contexto
- Menos respostas inventadas

Status:

-  Implementar

------

# Fase 5 - WhatsApp

## Objetivo

Atendimento real.

------

## Ferramentas

- WhatsApp Business
- Meta API
- Twilio

------

## Fluxo

```text
Cliente
    │
    ▼
WhatsApp
    │
    ▼
Copilot
    │
    ▼
Resposta
```

------

## Casos

Responder:

- Dúvidas
- Cursos
- Consultorias
- Eventos

Status:

-  Planejar

------

# Fase 6 - CRM

## Objetivo

Transformar conversas em oportunidades.

------

## Integrações

- HubSpot
- Salesforce
- Dynamics

------

## Funções

Registrar:

- Nome
- Empresa
- Interesse
- Tecnologia

------

## Exemplo

Cliente pergunta:

"Preciso de treinamento COBOL."

Ação:

Criar Lead.

Status:

-  Planejar

------

# Fase 7 - Mainframe Real

## Objetivo

Conectar o Copilot ao Mainframe.

------

## Integrações

- z/OS Connect
- MQ
- Kafka
- REST APIs
- CICS Web Services

------

## Exemplo

Pergunta:

"Qual o status do Job XYZ?"

Fluxo:

```text
Copilot
    │
    ▼
API
    │
    ▼
Mainframe
    │
    ▼
Resposta
```

------

## Casos Reais

Consultar:

- Jobs
- Filas MQ
- Aplicações
- CICS
- DB2

Status:

-  Futuro

------

# Melhorias Futuras

- IA com voz
- Avatar virtual
- Dashboard executivo
- Análise de sentimento
- Recomendação de cursos
- Recomendação de carreira
- Simulador de entrevistas COBOL
- Simulador de certificação IBM
- Tutor de JCL
- Tutor de RACF

------

# Critério de Sucesso

O Bellacosa Mainframe Sales Copilot será considerado bem-sucedido quando:

- Responder corretamente perguntas básicas.
- Tratar objeções sobre Mainframe.
- Apoiar oportunidades comerciais.
- Orientar estudantes.
- Utilizar a base de conhecimento.
- Reduzir dúvidas repetitivas.
- Melhorar a experiência do usuário.

------

# Visão Final

```text
Aluno
Empresa
Profissional
Gestor
      │
      ▼
Bellacosa Mainframe Sales Copilot
      │
      ▼
Conhecimento
Treinamento
Consultoria
Modernização
Carreira
      │
      ▼
Mainframe para Todos
```

☕🚀 "Transformando décadas de conhecimento Mainframe em conversas inteligentes."