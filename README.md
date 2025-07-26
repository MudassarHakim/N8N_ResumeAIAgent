## N8N GmailAutoEmail AI Agent — n8n Workflow

<img width="898" height="509" alt="Screenshot 2025-07-26 at 12 33 07 PM" src="https://github.com/user-attachments/assets/282b3d26-c831-4b42-a741-f304402f68fb" />


This workflow automates email replies using Google Gemini and Gmail.
- **Trigger:** Activates when a chat message is received.
- **AI Agent:** Uses Google Gemini to generate a reply, appends ‘regards, mudassar’.
- **Output:** Sends the generated message via Gmail.

### How to use:
1. Import `ResumeAIAgent.json` into your n8n instance.
2. Set up your own Google Gemini and Gmail credentials.
3. Test by triggering the webhook/chat endpoint.

**Note:** No credentials are included for security purposes.
