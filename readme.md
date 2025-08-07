
LangChain Lab
Este repositório contém uma série de scripts em Python projetados para servir como um laboratório de testes e aprendizado para a biblioteca LangChain, com foco na integração com a API do Groq.

Cada script demonstra um conceito fundamental da LangChain, permitindo que você explore e entenda como construir aplicações com LLMs.

Configuração do Ambiente
Antes de executar qualquer script, certifique-se de que você tem o Python instalado e de que as dependências do projeto estão configuradas.

Monte o ambiente:

python -m venv groq-chain
groq-chain/bin/activate

Desmontar ambiente:
Digite deactivate: e pressione Enter. 


Instale as dependências:

Bash

pip install -r requirements.txt

Configure as Chaves de API:

Você precisará de uma chave de API do Groq. Crie um arquivo .env na raiz do projeto e adicione sua chave.

Snippet de código

GROQ_API_KEY="SUA_CHAVE_AQUI"


# Aumente o timeout para baixa modelo de embedding do huggingface
export HF_HUB_DOWNLOAD_TIMEOUT=600