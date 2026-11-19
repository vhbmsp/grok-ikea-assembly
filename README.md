# IKEA Assembly Assistant

Modelo público de um Grok Bot que ajuda a montar mobiliário IKEA (e outros flat-pack) passo a passo, com instruções de voz opcionais baseadas nos manuais oficiais da IKEA.

> **🎙️ As instruções podem ser dadas por voz no Grok Bot, útil enquanto as mãos estão ocupadas a montar.**

## O que faz

O IKEA Assembly Assistant:

- procura o produto no site oficial da IKEA e abre o PDF de montagem;
- guia passo a passo em linguagem clara;
- acompanha o progresso, peças usadas e problemas;
- sugere ferramentas e lembra regras de segurança (anti-tip, parafusos corretos, etc.);
- oferece modo de voz no início de cada sessão, quando disponível.

## O que está no repositório

| Ficheiro | Função |
| --- | --- |
| `skills/ikea-assembly-getting-started/SKILL.md` | Primeira conversa: produto, número de artigo ou foto; oferece modo de voz. |
| `skills/ikea-assembly-guide/SKILL.md` | Guia de montagem a partir dos manuais oficiais IKEA. |
| `LICENSE` | Licença MIT. Copyright 2026 Vasco Pinheiro. |

## Como usar

### Opção 1 — Instalar diretamente pelo link

**[Importar o IKEA Assembly Assistant no Grok Bot](https://x.ai/bot/eB9uwq_-Ch7izIstZQHYx)**

Ao abrir o link, o bot é importado para o Grok Bot. A primeira conversa pede o produto (nome, número de artigo ou foto) e oferece o modo de voz.

### Opção 2 — Instalação manual a partir do repositório

1. Crie um bot novo no Grok Bot com o nome **IKEA Assembly Assistant**.
2. Adicione as duas skills deste repositório como skills do bot.
3. Inicie a conversa e diga o produto ou envie uma foto do manual.

## Credenciais e dados pessoais

Este repositório é um modelo partilhável. Não inclui dados pessoais.

---

# English

## What the bot does

IKEA Assembly Assistant is a public Grok Bot template that helps assemble IKEA and other flat-pack furniture step by step, with optional voice instructions based on official IKEA manuals.

> **🎙️ Voice instructions are available in Grok Bot — useful while your hands are busy assembling.**

## What's in the repo

| File | Role |
| --- | --- |
| `skills/ikea-assembly-getting-started/SKILL.md` | First chat: product name, article number or photo; offers voice mode. |
| `skills/ikea-assembly-guide/SKILL.md` | Assembly guidance from official IKEA instructions. |
| `LICENSE` | MIT License. Copyright 2026 Vasco Pinheiro. |

## How to use it

### Option 1 — Install directly from the link

**[Import IKEA Assembly Assistant into Grok Bot](https://x.ai/bot/eB9uwq_-Ch7izIstZQHYx)**

Opening it imports the bot into Grok Bot. The first conversation asks for the product (name, article number or photo) and offers voice mode.

### Option 2 — Manual installation from the repository

1. Create a new bot in Grok Bot named **IKEA Assembly Assistant**.
2. Add the two skills from this repository.
3. Start a conversation and tell it the product or send a photo of the manual.

## Credentials and personal data

This template includes no personal data.
