# Aplicação de Tradução de Documentos com Azure Translator - azure_translator

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

# Aplicação de Tradução de Artigo e geração em markdown com Azure OpenAI - azure_openai

Uma aplicação em Python que acessa um artigo através de uma URL, limpa o texto, traduz para o idioma escolhido pelo usuário e transforma o conteúdo em formato Markdown usando Azure OpenAI.

## Funcionalidades

- **Extrair Texto Limpo**: Acessa a URL do artigo e remove elementos indesejados (como scripts, estilos, etc.) para obter um texto limpo.
- **Tradução de Texto**: Permite ao usuário escolher para qual idioma deseja traduzir o texto.
- **Conversão para Markdown**: O texto traduzido é formatado em Markdown.

## Requisitos

- Python 3.7+
- Conta do **Azure Cognitive Services** com a API OpenAI configurada
- Jupyter Notebook
- Pacotes Python:
  - `requests`
  - `beautifulsoup4`
  -  `langchain-openai`

1. Clone este repositório:
   ```bash
   git clone https://github.com/DanilloAraujo/azure-translator-openai.git
