# SistemaAQI

<p align="center">
 <img src="https://github.com/user-attachments/assets/ed996709-f1cd-40b5-a41a-72c00161e10c" alt="screenshot" width="750">
</p>

- Sistema em desenvolvimento utilizando Python com o framework Flask
- O sistema possui um chatbot usando NLP (Processamento de Linguagem Natural) para responder perguntas sobre qualidade do ar e sustentabilidade.
- Checa a qualidade do ar em sua região em tempo real.

## Configuração inicial:
- Clone o repositório e crie um ambiente virtual
 ```
 python3 -m venv venv
 venv/bin/activate
 ```

- Instale as dependencias
```
$ (venv) pip install Flask torch torchvision nltk
```
  

  - Instale o pacote nltk:
  ```python
  (venv) python
  import nltk
  nltk.download('punkt')


