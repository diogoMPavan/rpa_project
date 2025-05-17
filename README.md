
# RPA Project - Coletor de Notícias do G1

Este projeto realiza a coleta automática da notícia mais recente do portal [G1](https://g1.globo.com/), salvando o título, data de publicação e resumo em arquivos `.json` e `.xlsx`.

## Como funciona

O script acessa a página inicial do G1, extrai a notícia mais recente e salva as informações em dois formatos:
- **noticia.json**: arquivo JSON com os dados coletados.
- **noticia.xlsx**: planilha Excel com os dados coletados.

## Requisitos

- Python 3.8+
- As bibliotecas listadas em `requirements.txt`

## Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/rpa_project.git
   cd rpa_project
   ```

2. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```

## Como usar

Execute o script principal:

```sh
python main.py
```

Os arquivos `noticia.json` e `noticia.xlsx` serão gerados na raiz do projeto.

## Estrutura

```
rpa_project/
│
├── src/
│   └── main.py
├── noticia.json
├── noticia.xlsx
├── requirements.txt
└── README.md
```
