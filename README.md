# WeydPédia

Projeto de recriação de uma página de artigo da Wikipédia, com foco em layout, responsividade e interação leve em JavaScript.

## Descrição

Este projeto simula uma página de enciclopédia com:

- cabeçalho com marca e busca
- índice lateral de navegação
- artigo em estilo editorial
- tabela de dados sobre o Sistema Solar
- destaque de seção ativa ao rolar a página
- busca local no texto
- alternância entre tema claro e escuro
- ajuste do tamanho da fonte
- suporte de impressão

## Estrutura do projeto

```text
.
├── index.html
└── README.md
```

## Como executar

### Opção 1: abrir diretamente no navegador

- basta abrir o arquivo `index.html` em um navegador moderno

### Opção 2: usar um servidor local

No terminal, na pasta do projeto, execute:

```bash
python -m http.server 8000
```

Depois abra no navegador:

```text
http://localhost:8000
```

## Funcionalidades principais

### Layout e responsividade
- página adaptada para desktop, tablet e mobile
- estrutura semelhante à Wikipedia com colunas laterais e artigo central

### Busca interna
- pesquisa por termos no conteúdo do artigo
- destaca ocorrências com marcação visual
- navega entre resultados com Enter
- limpa a busca com Esc

### Tema e leitura
- alterna entre modo claro e escuro
- salva a preferência no `localStorage`
- permite ajustar o tamanho da fonte do artigo

### Navegação
- índice lateral atualizado conforme a seção ativa
- links de navegação com destaque visual
- comportamento ajustado para dispositivos móveis

## Tecnologias utilizadas

- HTML
- CSS
- JavaScript

## Observações

O projeto foi desenvolvido como uma página estática, então não exige instalação de dependências nem build tools.

## Autor

Projeto criado para estudo e recriação de interface inspirada em enciclopédias web.
