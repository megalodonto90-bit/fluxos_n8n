# n8n WhatsApp AI Automation

Este repositório contém um workflow avançado desenvolvido no n8n para automação de atendimento via WhatsApp com uso de inteligência artificial, persistência de dados e integração com serviços externos.

## Visão Geral

O fluxo foi projetado para automatizar interações com clientes, interpretar mensagens, responder de forma inteligente e armazenar informações relevantes para acompanhamento e continuidade do atendimento.

## Funcionalidades

* Recebimento de mensagens via webhook
* Integração com API de WhatsApp (ex: Evolution API)
* Processamento de mensagens com inteligência artificial
* Respostas automáticas contextuais
* Armazenamento de dados em banco (Supabase)
* Memória de conversas para continuidade do atendimento
* Estrutura preparada para integração com agenda (Google Calendar)
* Organização de dados para possível uso em CRM

## Estrutura do Fluxo

O workflow é composto por:

* Webhook: entrada de mensagens
* Nodes de processamento: tratamento e estruturação dos dados
* Integração com IA: interpretação e geração de resposta
* Banco de dados: persistência de informações
* Envio de resposta: retorno ao usuário via API do WhatsApp

## Como Utilizar

1. Baixe o arquivo JSON do workflow
2. Importe no n8n:

   * Acesse o n8n
   * Clique em "Import workflow"
   * Selecione o arquivo JSON
3. Configure as credenciais necessárias:

   * API de WhatsApp
   * Serviço de IA
   * Supabase
   * Outros serviços utilizados
4. Ajuste variáveis como:

   * URL da API
   * Webhook
   * Identificadores
5. Ative o workflow

## Configurações Necessárias

Antes de utilizar, substitua os placeholders por seus dados reais:

* YOUR_API_URL
* YOUR_WEBHOOK_URL
* YOUR_WEBHOOK_HOST
* YOUR_API_KEY
* YOUR_PHONE_NUMBER
* YOUR_DOC_ID

## Segurança

Este repositório não contém credenciais reais. Todas as informações sensíveis foram substituídas por placeholders.

Recomendações:

* Nunca exponha API keys publicamente
* Utilize variáveis de ambiente sempre que possível
* Restrinja acesso aos webhooks
* Valide requisições externas

## Casos de Uso

* Atendimento automatizado para empresas
* Captura e qualificação de leads
* Suporte ao cliente
* Agendamento automatizado
* Integração com sistemas internos

## Observações

Este workflow pode ser adaptado para diferentes nichos, como clínicas, estética, serviços locais e atendimento comercial em geral.

## Autor

Vitor Hugo
