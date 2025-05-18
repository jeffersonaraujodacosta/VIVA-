# VIVA+ - Uma Conversa Diária para o Seu Bem-Estar

## Descrição

O VIVA+ é um sistema interativo baseado em inteligência artificial, desenvolvido com o modelo Gemini da Google, para promover o bem-estar e a autoconsciência do usuário através de uma conversa diária guiada. O sistema é composto por uma série de "agentes" de IA, cada um com uma função específica para ajudar o usuário a explorar seus sentimentos, definir intenções e refletir sobre seu dia.

## Funcionalidades

O VIVA+ guia o usuário através de uma conversa estruturada, envolvendo os seguintes agentes:

1.  **Radar Interno:** Inicia a conversa convidando o usuário a expressar seu estado emocional no início do dia.
2.  **Ação Consciente:** Com base no estado emocional do usuário, sugere microações, foco e autocuidado, além de fazer perguntas para entender melhor a situação.
3.  **Tarefas e Próximos Passos:** Propõe tarefas acionáveis e passos práticos com base no estado emocional e nas respostas anteriores do usuário.
4.  **Reflexão Momentânea:** Estimula a reflexão do usuário sobre o momento presente e sobre os insights ganhos durante a conversa.
5.  **Recompensa do Bem (Opcional):** Oferece uma mensagem final de encorajamento e positividade.

O sistema também simula o registro da interação, armazenando informações como o estado emocional do usuário, suas respostas e as tarefas definidas.

## Como Usar

1.  **Pré-requisitos:**
    * Uma conta Google.
    * Acesso ao Google Colaboratory (ou um ambiente Python com as bibliotecas necessárias instaladas).
    * Uma chave de API do Google Gemini configurada como um "Secret" no Google Colab com o nome `GOOGLE_API_KEY`.

2.  **Instalação:**
    * Abra o notebook do VIVA+ no Google Colaboratory.
    * Execute a célula para instalar a biblioteca `google-genai`:
        ```python
        !pip -q install google-genai
        ```
    * Certifique-se de ter configurado sua chave da API do Google Gemini como um "Secret" no Colab (Menu lateral -> Ícone de chave -> Adicionar um novo segredo)
