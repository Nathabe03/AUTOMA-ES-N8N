# 🤖 Agente de IA para Triagem e Atendimento Automatizado (n8n)

Este projeto implementa um **Agente de IA inteligente** utilizando o **n8n** e o **Google Gemini**, com foco em **classificação, priorização e resposta automatizada de clientes**.

O agente recebe mensagens via Webhook, interpreta o conteúdo com IA e toma decisões automáticas para direcionar o atendimento para os canais adequados.

---

## 🧠 O que o agente faz

- Recebe mensagens de clientes via Webhook
- Analisa o conteúdo usando um modelo de linguagem (Google Gemini)
- Classifica automaticamente o tipo de cliente:
  - Cliente comum
  - Cliente VIP
  - Cliente com reclamação
- Converte a resposta da IA em dados estruturados
- Executa lógica condicional (if/else) baseada na classificação
- Envia respostas personalizadas via:
  - Gmail
  - Telegram

---

## 📐 Arquitetura do fluxo

Webhook  
→ Agente de IA (Google Gemini)  
→ Analisador de saída estruturada  
→ Lógica condicional (Se / If)  
→ Ações automatizadas (E-mail e Telegram)

O fluxo foi projetado para manter o **Agente de IA focado apenas em análise e decisão**, enquanto as integrações externas são executadas fora do agente, garantindo maior estabilidade.

---

## 🛠️ Tecnologias utilizadas

- **n8n**
- **Google Gemini (Chat Model)**
- **Webhooks HTTP**
- **Google Sheets**
- **Gmail API**
- **Telegram Bot API**

---

## 🚀 Como usar

1. Importe o workflow JSON no n8n
2. Configure as credenciais necessárias (Google, Gmail, Telegram)
3. Ajuste o Webhook de entrada conforme sua aplicação
4. Ative o workflow

---

## 🔐 Segurança

Este repositório **não contém credenciais sensíveis**.  
Todas as chaves, tokens e URLs devem ser configuradas diretamente no n8n.

---

## 📸 Preview

> <img width="1577" height="712" alt="image" src="https://github.com/user-attachments/assets/cc5d9b33-8d9e-4572-8791-bff4ec163d39" />


---

## 📌 Objetivo do projeto

Demonstrar a criação de um **Agente de IA aplicado a um cenário real de atendimento**, utilizando automação, análise semântica e tomada de decisão baseada em IA.
