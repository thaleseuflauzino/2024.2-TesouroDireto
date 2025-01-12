# Forward From 

## Introdução

Este documento explora o método de rastreabilidade forward-from, essencial no desenvolvimento de sistemas. A rastreabilidade de requisitos conecta e monitora requisitos durante todo o ciclo de vida do sistema, facilitando a garantia da qualidade, a gestão de mudanças e o alinhamento com as demandas do cliente. O método forward-from enfatiza a criação de vínculos claros entre os requisitos, os desenhos do sistema e sua implementação.

## Metodologia

A metodologia adotada foi uma matriz de rastreabilidade com referências cruzadas, aplicada aos requisitos elicitados e aos artefatos gerados nas etapas de desenvolvimento do projeto. Como a relação entre requisitos e artefatos não é única, na matriz as linhas representam os requisitos, enquanto as colunas correspondem aos artefatos gerados.

Na aplicação do método forward-from, é utilizado o meta-modelo proposto por Toranzo, que organiza os requisitos identificados em diferentes níveis e elos. De acordo com os slides 19 da [aula 26](#REF1) ministrada pela professora Milene Serrano, os níveis são definidos da seguinte forma:

- **_Ambiental_**: Abrange informações derivadas do ambiente e contexto em que a organização opera.
- **_Organizacional_**: Refere-se a dados relacionados à estrutura e funcionamento da organização.
- **_Gerencial_**: Inclui informações que apoiam a gestão eficiente do projeto.
- **_Desenvolvimento_**: Envolve os dados associados aos artefatos gerados durante o processo de desenvolvimento.

Conforme descrito nos slides 21 da [aula 26](#REF1), os principais **elos de rastreabilidade** identificados são:

1. **Satisfação**: Representa a relação em que a classe de origem depende da satisfação proporcionada pela classe de destino.
2. **Recurso**: Define a dependência da classe de origem em relação aos recursos da classe de destino.
3. **Responsabilidade**: Documenta as ações, responsabilidades e participações de indivíduos sobre os artefatos.
4. **Representação**: Descreve como os requisitos são expressos ou modelados em linguagens alternativas.
5. **Alocado**: Estabelece a ligação entre a classe de origem e uma classe de destino correspondente a um subsistema.
6. **Agregação**: Representa a composição de elementos que constituem o sistema.

Para estruturar a criação do meta-modelo de Toranzo, foram desenvolvidas as **tabelas 1 e 2**.

## Matriz de Rastreabilidade 

A tabela 1 representa a matriz de rastreabilidade.

## Elos 

A tabela 2 mostra os elos entre os requisitos elicitados e os artefatos do projeto.

## Referência Bibliografia

> <a id="REF1">1.</a> Requirements Engineering Fundamentals. Disponível em: [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 12 jan. 2025.

> <a id="REF2">2.</a> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 12 jan. 2025.

## Bibliografia

> 1. Economia DF - "Rastreabilidade - Forward From". Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/forward_from/](https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/forward_from/). Acesso em: 12 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|12/01/2025|Criação e ajuste do Documento|[Victor Rodrigues](https://github.com/ViictorHugoo)||
