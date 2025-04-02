# Laboratórios de Serviços de IA do Azure

Este repositório é dedicado à publicação de laboratórios relacionados aos serviços de Inteligência Artificial (IA) do Azure. Ele contém exemplos práticos e tutoriais que demonstram como utilizar os serviços de IA do Azure para resolver problemas reais em diferentes áreas, como visão computacional, processamento de linguagem natural e análise de texto.

## Estrutura do Repositório

- **DOC-INTELIGENCE/**: Projetos relacionados à inteligência de documentos.
  - **custom-document-intelligence/**: Exemplos de uso de modelos personalizados para análise de documentos.
  - **prebuild-model-invoice/**: Demonstração de modelos pré-construídos para extração de informações de faturas.
  - **prebuild-model-read/**: Uso de modelos pré-construídos para leitura e extração de texto.

- **IA-SEARCH/**: Projetos focados em soluções de busca inteligente utilizando IA.

- **IA-VISION/**: Laboratórios relacionados à visão computacional.
  - **analyze-images/**: Exemplos de análise de imagens utilizando serviços do Azure.
  - **custom-vision/**: Projetos que utilizam o Custom Vision para criar modelos personalizados de classificação de imagens.
  - **Image-classification/**: Demonstrações de classificação de imagens com modelos pré-treinados.

- **NLP-LAB/**: Projetos de Processamento de Linguagem Natural (NLP).
  - **analyze-text/**: Scripts e dados para análise de texto.
  - **extrair-entidades-custom-entity-recognition/**: Extração de entidades personalizadas utilizando serviços de reconhecimento de entidades.
  - **language-coloquial/**: Processamento de linguagem coloquial para análise de texto informal.
  - **speech/**: Reconhecimento de fala utilizando serviços do Azure.
  - **speech-translation/**: Tradução de fala em tempo real.
  - **text-classification/**: Classificação de texto com modelos personalizados e pré-treinados.

- **env/**: Ambiente virtual Python configurado com as dependências necessárias para executar os laboratórios.

**Mais laboratórios serão adicionados a este repositório futuramente.**

## Requisitos

Para executar os exemplos e tutoriais deste repositório, você precisará ter o Python instalado e configurar um ambiente virtual. As dependências necessárias estão listadas no arquivo `requirements.txt`.

## Configuração do Ambiente

1. Crie e ative um ambiente virtual:
    ```bash
    python -m venv env
    source env/bin/activate  # No Windows, use `env\Scripts\activate`
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

## Contribuição

Este projeto acolhe contribuições e sugestões. Para contribuir, por favor, siga as diretrizes descritas no Código de Conduta.

## Licença

Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo LICENSE para mais detalhes.