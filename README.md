# NEXO PORSCHE | Sales Intelligence Dashboard

Dashboard interativa desenvolvida para transformar uma base comercial sanitizada em uma análise visual, navegável e contextualizada.

O projeto permite explorar os registros por modelo Porsche, cidade, ano do veículo, método de pagamento e período da venda. Mais do que apresentar números, a proposta foi construir uma experiência que ajudasse a compreender o que os dados realmente mostram — inclusive suas limitações.

> **NEXO · Dados com contexto. Soluções com intenção.**

## Acesse o projeto

🔗 [Visualizar a dashboard](https://marianbsantana.github.io/nexo-porsche-dashboard/)

## Visão geral

A dashboard faz parte da minha linha de projetos NEXO e foi desenvolvida durante o desafio **“Criando uma Dashboard da Porsche com Agentes de IA”**, da DIO.

A base original foi tratada e incorporada ao próprio HTML. Dessa forma, a aplicação pode funcionar diretamente no navegador, sem depender de servidor, banco de dados ou envio separado da planilha.

## Funcionalidades

* Filtros combinados por modelo, cidade, ano e método de pagamento;
* Seleção personalizada do período de vendas;
* Indicadores de receita, vendas, cidades e modelos;
* Comparação do faturamento mensal;
* Ranking dos modelos mais frequentes;
* Análise da presença comercial por cidade;
* Série temporal do ritmo de vendas;
* Identificação dos modelos líderes em cada cidade;
* Leitura automática do recorte selecionado;
* Tooltips com informações contextualizadas;
* Alternância entre os temas claro e escuro;
* Limpeza rápida dos filtros;
* Geração de relatório em formato A4 pela impressão do navegador;
* Layout responsivo para diferentes tamanhos de tela.

## Decisões de análise

Para preservar a coerência dos indicadores, foram estabelecidos alguns critérios:

* Registros cancelados são excluídos das vendas e da receita;
* Datas inválidas não entram na série temporal;
* Registros não cancelados podem incluir entregas ainda pendentes;
* Popularidade representa frequência dentro da amostra analisada;
* Empates entre modelos são preservados;
* Amostras locais pequenas são sinalizadas para evitar interpretações exageradas;
* Receita representa a soma dos valores presentes na base e não uma informação contábil oficial.

A base contém **100 registros únicos**. Desse total, **7 registros cancelados** são excluídos dos indicadores comerciais. Os registros sem data válida permanecem nos totais quando atendem aos demais critérios, mas não participam das análises temporais.

## Tecnologias e recursos

* HTML5;
* CSS3;
* JavaScript;
* Manipulação e filtragem de dados no navegador;
* Desenvolvimento e revisão com apoio de agentes de inteligência artificial;
* GitHub Pages para publicação.

## Estrutura do projeto

```text
nexo-porsche-dashboard/
├── index.html
├── README.md
└── assets/
    └── imagens-do-projeto
```

Os dados necessários para o funcionamento da dashboard estão incorporados ao arquivo `index.html`.

## Como executar

1. Faça o download ou clone este repositório;
2. Localize o arquivo `index.html`;
3. Abra o arquivo em um navegador atualizado.

Não é necessário instalar dependências.

## Base utilizada

Base Porsche sanitizada disponibilizada como material complementar do projeto da DIO:

[Baixar a planilha original](https://hermes.dio.me/files/assets/8683bed0-cc33-4e06-bca9-04db9c31f9e2.xlsx)

## Aprendizados

Este projeto me permitiu praticar:

* Estruturação de uma dashboard em HTML;
* Transformação de dados em indicadores úteis;
* Criação de filtros interativos;
* Tratamento de registros cancelados e datas inválidas;
* Comunicação de limitações da base;
* Organização da informação para facilitar a tomada de decisão;
* Uso de IA como apoio ao desenvolvimento, à validação e ao refinamento do projeto;
* Construção de uma identidade visual consistente com meu portfólio.

## Autoria

Desenvolvido por **Marian Sant’Ana**.

Este é um projeto educacional e independente, criado a partir de uma base sanitizada disponibilizada pela DIO. Não possui vínculo oficial com a Porsche AG.

---

**NEXO · Dados com contexto. Soluções com intenção.**
