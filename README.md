# Conversor de Moedas

>   Uma aplicação web que permite converter valores entre diferentes moedas de forma fácil e rápida.

O projeto oferece uma interface intuitiva para inserir o valor, escolher as moedas de origem e destino, e visualizar o resultado da conversão, além de manter um histórico das conversões realizadas.

<a href="https://vitoriapguimaraes.github.io/HTML_CSS_Javascript-ConversorMoeda/"><img src="https://img.shields.io/badge/-Conversor%20de%20Moeda-000000?style=for-the-badge" alt="HTML_CSS_Javascript-ConversorMoeda">

![Tela do sistema](https://github.com/vitoriapguimaraes/HTML_CSS_Javascript-ConversorMoeda/blob/main/results/converter.gif)

## Funcionalidades Principais:

-   Converte valores entre diferentes moedas.
-   Permite ao usuário selecionar a moeda de origem e a moeda de destino.
-   Exibe o resultado da conversão de forma clara.
-   Valida a entrada de dados para garantir que os campos sejam preenchidos corretamente.
-   Mantém um histórico das conversões realizadas.
-   Permite exportar o histórico de conversões para um arquivo .txt.

## Tecnologias Utilizadas:

-   HTML5
-   CSS3
-   JavaScript
-   API de Câmbio (https://api.currencyapi.com/v3/)

## Como Executar:

1.  Clone o repositório
2.  Navegue até o diretório do projeto.
3.  Crie sua [chave da API](https://api.currencyapi.com/v3/).
4.  Crie um arquivo `config.js` para definir a chave (`const API_KEY =`) e adicione a chave criada.
5.  Abra o arquivo `index.html` no seu navegador.

## Como Usar:

1.  Selecione a moeda de origem no primeiro campo de seleção.
2.  Insira o valor que deseja converter no campo de entrada.
3.  Selecione a moeda de destino no segundo campo de seleção.
4.  Clique no botão "Converter" para realizar a conversão.
5.  O resultado da conversão será exibido na tela.
6.  O histórico de conversões é exibido em uma tabela abaixo do conversor.
7.  Clique no botão "Exportar como .txt" para baixar o histórico de conversões em um arquivo de texto.

## Estrutura de Diretórios:

```
/conversor-de-moedas
├── index.html
├── src
│   ├── styles.css
│   ├── script.js
│   └── config.js          # Arquivo de configuração (API Key)
├── results/                # Prints e gifs do software
└── README.md
```

## Status:

✅ Concluído

>   Melhorias que podem ser incluídas:
>
>   -   Adicionar funcionalidade para inverter as moedas de origem e destino.
>   -   Implementar validações em tempo real dos campos de entrada.
>   -   Adicionar mais opções de formatação para os resultados (ex: diferentes números de casas decimais).
>   -   Melhorias de acessibilidade na interface.

## Mais Sobre Mim:

Acesse os arquivos disponíveis na [Pasta Documentos](https://github.com/vitoriapguimaraes/vitoriapguimaraes/tree/main/DOCUMENTOS) para mais informações sobre minhas qualificações e certificações.
