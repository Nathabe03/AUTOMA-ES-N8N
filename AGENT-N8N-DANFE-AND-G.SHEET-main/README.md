AGENTE IA – Classificação Automática de Notas Fiscais com Gemini, Gmail e Google Sheets

Este projeto implementa uma automação inteligente com n8n que recebe notas fiscais por e-mail , analisa o conteúdo utilizando IA generativa (Google Gemini) e organiza automaticamente os arquivos no Google Drive , além de registrar os dados estruturados em uma planilha de controle de faturas no Google Sheets.

A automação foi projetada para eliminar processos manuais de triagem, classificação e lançamento de notas fiscais, garantindo organização, rastreabilidade e escalabilidade.
__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
🧠 Tecnologias Utilizadas

.n8n – Orquestração da automação
.Google Gemini (IA Generativa) – Classificação e análise inteligente dos documentos
.Gmail Trigger – Entrada automatizada via e-mail
.Google Drive – Armazenamento e organização dos arquivos
.Planilhas Google – Registro e controle das faturas
.Loops e decisões condicionais – Processamento robusto de múltiplos documentos

📷 Visão do Workflow

A imagem abaixo representa o fluxo completo da automação no n8n, desde a coleta do e-mail até o armazenamento e registro das notas fiscais.

<img width="851" height="381" alt="workflow danfe g sheet" src="https://github.com/user-attachments/assets/1017931b-50c5-4193-886e-5066bb4199cc" />


___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

⚠️ Este workflow não funciona imediatamente após a importação.

Por motivos de segurança, credenciais, IDs de pastas e planilhas
não estão incluídos no JSON.

Após importar, configure:
- Gmail OAuth2
- Google Drive OAuth2
- Google Sheets OAuth2
- Google Gemini API
