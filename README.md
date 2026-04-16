[README_CalendarAI.md](https://github.com/user-attachments/files/26772042/README_CalendarAI.md)# CalendarAI Assistant

> Agente de IA com memória contextual que consulta sua agenda em tempo real, responde perguntas sobre eventos e envia emails automaticamente — como um assistente pessoal inteligente.

---

##  Sobre o projeto

O **CalendarAI Assistant** é um agente de IA construído com **n8n** que simula um assistente pessoal inteligente com acesso à sua agenda e email.

O diferencial deste projeto está na **memória contextual** — o agente lembra do contexto da conversa entre interações, tornando o diálogo natural e fluido. Ele consulta o **Google Calendar** em tempo real para responder perguntas sobre eventos, horários e compromissos, e pode enviar **emails via Gmail** automaticamente quando solicitado.

---

##  Como funciona

```
Usuário envia uma pergunta ou comando
               ↓
Agente n8n processa com memória contextual
               ↓
        ┌──────────────────────┐
        │ Pergunta sobre agenda?│
        │ → Consulta Google     │
        │   Calendar em tempo   │
        │   real e responde     │
        │                      │
        │ Pede para enviar      │
        │ email?               │
        │ → Gera e envia via    │
        │   Gmail               │
        └──────────────────────┘
               ↓
Resposta entregue com contexto da conversa
```

---

##  Tecnologias utilizadas

| Ferramenta | Função |
|---|---|
| [n8n](https://n8n.io) | Orquestração do agente e fluxo de automação |
| [n8n AI Agent](https://docs.n8n.io/advanced-ai/) | Agente com memória contextual entre conversas |
| [Google Calendar API](https://developers.google.com/calendar) | Consulta de eventos e compromissos em tempo real |
| [Gmail API](https://developers.google.com/gmail) | Envio automático de emails |

---

##  Funcionalidades

- ✅ Consulta eventos do Google Calendar em tempo real
- ✅ Responde perguntas sobre compromissos, horários e agenda
- ✅ Envia emails automaticamente via Gmail
- ✅ Memória contextual — lembra do contexto entre interações
- ✅ Simula um assistente pessoal inteligente
- ✅ Fluxo 100% no-code via n8n

---

##  Exemplos de uso

> "Quais são meus compromissos de amanhã?"

> "Tenho alguma reunião na sexta à tarde?"

> "Manda um email para o João confirmando a reunião de segunda."

---

##  Como usar

### Pré-requisitos

- Conta no [n8n](https://n8n.io) (self-hosted ou cloud)
- Conta Google com Google Calendar API e Gmail API habilitadas

### Configuração

1. Clone este repositório
2. Importe o arquivo `index (2)` no n8n
3. Configure as credenciais:
   - Google Calendar OAuth2
   - Gmail OAuth2
4. Ative o workflow e inicie uma conversa com o agente

---

##  Estrutura do projeto

```
CalendarAI-Assistant/
├── index (2)       # Fluxo exportado do n8n
└── README.md
```

---

##  Autor

**João Pedro Silva dos Santos**  
[GitHub](https://github.com/JoaoPedroske) · [Email](mailto:joaopedrosilvadossantos94@gmail.com)

---

##  Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

