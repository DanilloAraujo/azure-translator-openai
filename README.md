# Aplicação de Tradução de Documentos com Azure Translator

Este é um projeto de tradução de documentos `.docx` de um idioma para outro usando a API do **Azure Translator**. O projeto é implementado em Python como um notebook Jupyter interativo, permitindo que o usuário carregue um documento `.docx`, escolha os idiomas de origem e destino, e baixe o documento traduzido diretamente.

## Funcionalidades

- **Carregamento de Documento**: Suporta upload de arquivos `.docx`.
- **Tradução via Azure Translator**: Traduz texto do documento de um idioma para outro.
- **Download Direto**: Permite que o usuário baixe o documento traduzido diretamente pelo notebook.
- **Notificações Interativas**: Exibe uma mensagem para o usuário confirmando o upload e avisando quando o documento está pronto para tradução.

## Requisitos

- Python 3.7+
- Conta do **Azure Cognitive Services** com a API Translator configurada
- Jupyter Notebook
- Pacotes Python:
  - `requests`
  - `python-docx`
  - `ipywidgets`

## Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/DanilloAraujo/azure-translator-openai.git
   cd projeto-tradutor
