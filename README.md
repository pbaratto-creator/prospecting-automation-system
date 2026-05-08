# Sistema de Automação de Prospecção

Fluxo automatizado para geração de leads comerciais utilizando Google Maps, Apify, Make e Google Sheets.

---

## Funcionalidades

- Extração automatizada de empresas
- Filtro por nicho e localização
- Organização automática em Google Sheets
- Geração automática de links de WhatsApp
- Pipeline de prospecção automatizado
- Estrutura preparada para futuras automações

---

## Arquitetura Atual

Apify
↓
Make
↓
Google Sheets
↓
WhatsApp Links

---

## Stack Utilizada

- Apify
- Make
- Google Sheets
- Google Maps Scraping

---

## Fluxo do Sistema

1. Busca empresas por nicho e cidade
2. Extrai dados comerciais
3. Organiza os leads automaticamente
4. Gera links rápidos de WhatsApp
5. Facilita contato comercial em escala

---

## Melhorias Futuras

- [ ] Migração do scraping para Python
- [ ] Mini CRM
- [ ] Controle de status dos leads
- [ ] Automação de follow-up
- [ ] Dashboard
- [ ] Integração com IA

---

## Objetivo do Projeto

Automação, scraping, integração entre APIs e pipelines de prospecção comercial.


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
