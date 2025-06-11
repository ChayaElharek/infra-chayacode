# AIChatBot-Flow

Este fluxo automatizado do n8n atua como um atendente virtual com inteligência artificial, utilizando integração com o Groq, Chatwoot e Google Sheets.

## ✨ Funcionalidades

- Recebe mensagens via webhook do WhatsApp (Evolution API)
- Usa IA para gerar respostas personalizadas (Groq + Langchain)
- Registra todas as conversas em planilhas Google (Google Sheets)
- Mantém contexto da conversa com memória
- Utiliza ferramentas auxiliares como Wikipedia e Calculadora

## 📦 Requisitos

- Conta ativa no [n8n.io](https://n8n.io)
- Credenciais da Evolution API ou outro provedor de WhatsApp
- Conta e credenciais de Google Sheets configuradas no n8n
- Chave de API do Groq
- Docker (opcional)

## 🚀 Como usar

1. Importe o fluxo `.json` no seu painel n8n
2. Configure as credenciais (Groq, Google Sheets, Evolution API)
3. Ative o fluxo
4. Teste enviando mensagens para o webhook configurado

## 📁 Estrutura

```
automations/
└── AIChatBot-Flow/
    ├── AIChatBot-Flow.json
    └── README.md
```

## 📍 Observações

- Esse fluxo é ideal para testes de chatbots inteligentes com histórico de conversa.
- Pode ser integrado com sistemas de CRM ou suporte técnico facilmente.
