# Matriz de Rastreablidade 

## Introdução 

Uma Matriz de Rastreabilidade de Requisitos é um documento estruturado em formato de tabela que conecta os requisitos de um projeto a outros artefatos, como casos de teste, códigos fonte e documentos de design. Essa matriz permite rastrear a origem, evolução e implementação de cada requisito, destacando dependências e inter-relações entre eles.

Sua aplicação é essencial devido à complexidade dos projetos de software e às mudanças constantes, garantindo controle e clareza desde a concepção dos requisitos até a entrega final. Além disso, ela facilita a compreensão, monitoramento e gestão, evidenciando as conexões entre os elementos do projeto e oferecendo uma visão completa e organizada.

## Metodologia

A Matriz de Rastreabilidade de Requisitos é construída a partir da análise detalhada dos documentos relacionados ao projeto e organiza os requisitos em colunas que fornecem informações essenciais para sua gestão. As colunas incluem:

- Código: Identificador do requisito analisado.
- Tipo: Classificação como requisito funcional (RF) ou não funcional (RNF).
- Descrição: Definição do requisito ou artefato correspondente.
- Pré-Rastreabilidade: Origem do requisito elicitado.
- Implementado?: Estado de implementação do requisito (Sim ou Não).
- Artefatos: Lista de artefatos que fazem referência ao requisito.
- Elos: Conexões entre requisitos e artefatos nos documentos [Backward From](./backward-from.md) e [Forward From](./forward-from.md).

## Matriz de Rastreabilidade 

| Código | Tipo | Descrição | Pré-rastreabilidade | Implementado | Artefatos | Elos |
| ------ | ---- | --------- | ------------------- | ------------ | --------- | ---- | 

## Bibliografia

>  Requirements Engineering Fundamentals. Disponível em: [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 14 jan. 2025.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 14 jan. 2025.

> Economia DF - "Rastreabilidade - Matriz de Rastreabilidade". Disponível em: [requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade](requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade). Acesso em: 14 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/01/2025| Criação e ajuste do Documento |[Victor Rodrigues](https://github.com/ViictorHugoo) | |