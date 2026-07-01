# Assistente de IA Jurídica - Distrito Federal

Projeto de **RAG (Retrieval-Augmented Generation)** para análise e sumarização de documentos jurídicos e processos administrativos do Distrito Federal (GDF).

**Foco inicial**: Portarias e normas da Secretaria de Educação (e outros órgãos do GDF).

## Objetivo

Criar um assistente que:
- Analise PDFs de leis, portarias, decretos e editais
- Faça resumos inteligentes
- Responda perguntas em linguagem natural
- Sempre cite as fontes (reduzindo alucinações)

## Status Atual

**Fase 1** (em andamento): Coleta, extração e preparação dos dados.

## Estrutura do Projeto

```bash
assistente-ia-juridico/
├── data/
│   ├── raw/          # PDFs originais
│   ├── processed/    # Textos extraídos
│   └── metadata/     # Arquivos CSV/JSON com informações
├── notebooks/        # Jupyter notebooks de exploração
├── src/
│   └── data/         # Scripts de extração e chunking
├── requirements.txt
├── .gitignore
└── README.md
