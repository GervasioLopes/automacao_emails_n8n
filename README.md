# Automação de Envio de E-mails com n8n

Projeto de automação desenvolvido utilizando **n8n** para realizar o processamento de informações provenientes de uma tabela de dados (Google Sheets) e executar o envio automatizado de e-mails personalidades de confirmação/boas-vindas via Gmail[cite: 1, 2].

---

## 📌 Fluxo de Funcionamento

1. **Gatilho (Google Sheets Trigger):** Monitoriza novas respostas adicionadas a uma planilha associada a um formulário[cite: 1].
2. **Processamento & Personalização:** Extrai dados do novo contacto, como o nome do cliente, empresa e áreas de interesse[cite: 1].
3. **Envio (Gmail):** Dispara uma mensagem personalizada com o resumo das informações e próximos passos[cite: 1].

---

## 🛠️ Tecnologias Utilizadas

- **[n8n](https://n8n.io/):** Plataforma de automação de fluxos de trabalho[cite: 1, 2].
- **Google Sheets:** Origem e captura dos dados[cite: 1].
- **Gmail:** Serviço de envio dos e-mails[cite: 1].

---

## 🚀 Como Importar e Utilizar

1. **Transferir o Workflow:**
   - Transfere o ficheiro [`n8n_enviodeEmail02.json`](./n8n_enviodeEmail02.json) presente neste repositório.

2. **Importar no n8n:**
   - Abre a tua instância do n8n.
   - Acede ao menu **Workflows** > **Import from File...** e seleciona o ficheiro `.json`[cite: 2].

3. **Configurar Credenciais:**
   - Conecta a tua conta do **Google Sheets** no nó de trigger[cite: 1].
   - Conecta a tua conta do **Gmail** no nó de envio de e-mail[cite: 1].

4. **Ajustar Parâmetros:**
   - Substitui o ID/URL da planilha Google Sheets no nó de gatilho[cite: 1].
   - Personaliza o corpo do e-mail e os links no nó do Gmail conforme necessário[cite: 1].
   - Ativa o workflow!
