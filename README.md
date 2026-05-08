# Sistema de Automação de Prospecção

Sistema de automação para geração e organização de leads comerciais utilizando Google Maps, Apify, Make e Google Sheets.

O projeto automatiza a coleta de empresas, organização dos dados e geração de contatos rápidos via WhatsApp para prospecção comercial.

---

# Funcionalidades Atuais

- Extração automatizada de empresas
- Busca por nicho e localização
- Organização automática dos leads em Google Sheets
- Geração automática de links de WhatsApp
- Abertura semi automática de conversa com mensagem pré-preenchida
- Pipeline automatizado de prospecção comercial
- Estrutura modular para futuras automações

---

# Arquitetura Atual

Apify  
↓  
Make  
↓  
Google Sheets  
↓  
WhatsApp Automation

---

# Stack Utilizada

- Apify
- Make
- Google Sheets
- Google Maps Scraping
- WhatsApp Links Automation

---

# Fluxo do Sistema

1. Busca empresas por nicho e cidade
2. Extrai dados comerciais automaticamente
3. Organiza os leads no Google Sheets
4. Gera links automáticos de contato via WhatsApp
5. Preenche mensagens automaticamente para prospecção

---

# Objetivo do Projeto

O objetivo do projeto é aplicar automação, integração entre plataformas, scraping de dados comerciais e construção de pipelines de prospecção automatizada.


## Screenshots

### Fluxo da automação

Fluxo principal responsável pela coleta e organização automática dos leads.

![Fluxo da automação](make%20estrutura.png)


## Google Sheets Output

### Organização automática dos leads

Exemplo da estrutura gerada automaticamente no Google Sheets após o processamento dos dados coletados.

O sistema organiza:

- nome da empresa
- nicho
- cidade
- telefone
- website
- link direto de WhatsApp
- status do lead

A automação transforma dados brutos em uma base pronta para prospecção comercial.

![Google Sheets](print%20sheets.png)


## Automação WhatsApp

### Início automatizado de contato

Exemplo da geração automática de conversas no WhatsApp utilizando links criados pelo fluxo de automação.

O sistema transforma contatos comerciais coletados em conversas prontas para abordagem, acelerando o processo de prospecção.

![Google Sheets](print%20whatzap1.png)
![Google Sheets](print%20whatzap.png)


# Possiveis melhorias Futuras

- [ ] Migração parcial ou total para Python
- [ ] Mini CRM integrado
- [ ] Controle de status dos leads
- [ ] Dashboard de métricas
- [ ] Follow-up automatizado
- [ ] Integração com APIs oficiais do WhatsApp
- [ ] Segmentação avançada de leads
- [ ] Integração com IA para qualificação de leads
