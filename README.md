# girlfriend-answerer
Chatbot criado para responder minha namorada quando eu estiver nas minhas ranqueadas no lolzinho! - integração a caminho
![Imagem](https://i.imgur.com/ek4X2wM.png "Title")

- PYTHON
- CHATTERBOT
- SPACY


# CORREÇÃO DA INCOMPATIBILIDADE DO CHATTERBOT COM O SPACY NESSA VERSÃO
from spacy.cli import download

download("en_core_web_sm")

class ENGSM:
    ISO_639_1 = 'en_core_web_sm'
