# SistemaAQI

<p align="center">
  <img src="https://github.com/user-attachments/assets/e7790e91-c4b4-49f9-8e4c-a968cd480af8" alt="icongit" width="750">
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


