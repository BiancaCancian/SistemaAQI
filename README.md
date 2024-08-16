# SistemaAQI

<p align="center">
 <img src="https://github.com/user-attachments/assets/2a6c1e58-a71f-4d4e-af52-8e01b24f5917" alt="screenshot" width="750">
</p>

- Sistema em desenvolvimento utilizando Python com o framework Flask
- O sistema possui um chatbot usando NLP (Processamento de Linguagem Natural) para responder perguntas sobre qualidade do ar e sustentabilidade.
- Checa a qualidade do ar em sua região em tempo real.

## Configuração inicial:
- Clone o repositório e crie um ambiente virtual.
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


