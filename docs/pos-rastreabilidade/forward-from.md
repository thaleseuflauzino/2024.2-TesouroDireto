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

**Legenda:**

> - RF - Requisito Funcional
> - RNF - Requisito não Funcional
> - UC - Caso de Uso 
> - CEN - Cenários
> - F, U, C, S, P - Especificação Suplementar
> - L - Léxicos
> - NFR - NFR Framework
> - EC - Épico 
> - FT - Feature
> - HS - História de Usuário

<center>

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Matriz de rastreabilidade Foward-From</p></font>

| Requisito e Versão | Tipo | Implementado | Caso de Uso | Cenários | Especificação Suplementar | Léxicos | NFR Framework | Épico | Feature | História de Usuário | Elo Relacionado |
| ------------------ | ---- | ------------ | ----------- | -------- | ------------------------- | ------- | ------------- | ----- | ------- | ------------------- | --------------- |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF01">RF01<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC06</a> | | | L01, L03, L04 | | EC01 | FT01, FT02 | US01 | ELOF01 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">RF02<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC02</a> | <a href="../../modelagem-pt1/cenarios/">CEN01<a/> | | L02, L03, L05 | | EC03 | FT06 | US19 | ELOF02 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF03">RF03<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC07</a> | <a href="../../modelagem-pt1/cenarios/">CEN02<a/> | | | | EC07 | FT14 | US03 | ELOF03 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF04">RF04<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC08</a> | <a href="../../modelagem-pt1/cenarios/">CEN03<a/> | | | | EC09 | FT18 | US04 | ELOF04 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF05">RF05<a/> / `1.4` | RF |  Sim  | | <a href="../../modelagem-pt1/cenarios/">CEN04<a/> | | | | EC10 | FT20 | US05 | ELOF05 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF06">RF06<a/> / `1.4` | RF |  Sim  | | | | L02, L05 | | EC04 | FT07 | US06 | ELOF06 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF08">RF08<a/> / `1.4` | RF |  Sim  | | <a href="../../modelagem-pt1/cenarios/">CEN05<a/> | | L02, L05 | | EC07 | FT14 | US07 | ELOF08 | 
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF09">RF09<a/> / `1.4` | RF |  Sim  | | | | | | EC12 | FT25 | US08 | ELOF09 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF12">RF12<a/> / `1.4` | RF |  Sim  | | | | L02, L05 | | EC11 | FT23 | US09 | ELOF12 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF13">RF13<a/> / `1.4` | RF |  Não  | | | | L05 | | EC07, EC12 | FT15, FT26 | US10 | ELOF13 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF14">RF14<a/> / `1.4` | RF |  Não  | | | | L02, L05 | | EC02 | FT04 | US11 | ELOF14 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF15">RF15<a/> / `1.4` | RF |  Não  | <a href="../../modelagem-pt1/casos-de-uso">UC10</a> | <a href="../../modelagem-pt1/cenarios/">CEN09<a/> | | L04 | | EC04 | FT07 | US12 | ELOF15 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF16">RF16<a/> / `1.4` | RF |  Não  | | | | | | EC08 | FT16 | US13 | ELOF16 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF17">RF17<a/> / `1.4` | RF |  Não  | | | | | | EC02 | FT04 | US14 | ELOF17 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF18">RF18<a/> / `1.4` | RF |  Não  | | | | L05 | | EC15 | FT31 | US15 | ELOF18 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF20">RF20<a/> / `1.4` | RF |  Não  | | | | | | EC05 | FT09 | US16 | ELOF20 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF21">RF21<a/> / `1.4` | RF |  Não  | | | | | | EC08 | FT17 | US17 | ELOF21 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF23">RF23<a/> / `1.4` | RF |  Não  | | <a href="../../modelagem-pt1/cenarios/">CEN07<a/> | | | | EC03 | FT05 | US18 | ELOF23 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF24">RF24<a/> / `1.4` | RF |  Sim  | | | | L03 | | EC03 | FT06 | US19 | ELOF24 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF25">RF25<a/> / `1.4` | RF |  Não  | <a href="../../modelagem-pt1/casos-de-uso">UC09</a> | <a href="../../modelagem-pt1/cenarios/">CEN08<a/> | | L06 | | EC09 | FT19 | US20 | ELOF25 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF26">RF26<a/> / `1.4` | RF |  Não  | <a href="../../modelagem-pt1/casos-de-uso">UC11</a> | <a href="../../modelagem-pt1/cenarios/">CEN26<a/> | | | | EC04 | FT08 | US21 | ELOF26 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF27">RF27<a/> / `1.4` | RF |  Não  | | | | | | EC09 | FT19 | US22 | ELOF27 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF28">RF28<a/> / `1.4` | RF |  Não  | | | | | | EC10 | FT21 | US23 | ELOF28 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF29">RF29<a/> / `1.4` | RF |  Não  | | | | | | EC05 | FT11 | US10 | ELOF29 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF31">RF31<a/> / `1.4` | RF |  Sim  | | | | | | EC07 | FT14 | US25 | ELOF31 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF32">RF32<a/> / `1.4` | RF |  Sim  | | | | | | EC04 | FT07 | US26 | ELOF32 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF33">RF33<a/> / `1.4` | RF |  Não  | <a href="../../modelagem-pt1/casos-de-uso">UC01</a> | | | | | EC05 | FT09 | US27 | ELOF33 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF34">RF34<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC01</a> | | | L05 | | EC05 | FT09 | US28 | ELOF34 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF35">RF35<a/> / `1.4` | RF |  Sim  | <a href="../../modelagem-pt1/casos-de-uso">UC03</a> | | | | | EC02 | FT03  | US29  | ELOF35 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF36">RF36<a/> / `1.4` | RF |  Sim  | | | | | | EC01, EC15 | FT01, FT32 | US15 | ELOF36 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF37">RF37<a/> / `1.4` | RF |  Sim  | | | | | | EC03 | FT06 | US02, US33 | ELOF37 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF39">RF38<a/> / `1.4` | RF |  Sim  | | | | L01 | | EC03 | FT05 | US32 | ELOF38 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF39">RF39<a/> / `1.4` | RF |  Sim  | | | | L01 | | EC03 | FT05 | US31 | ELOF39 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF40">RF40<a/> / `1.4` | RF |  Não  | | | | | | EC09 | FT19 | US34 | ELOF40 |
| <a href="../../elicitacao/grupo5/requisitos/#anchor_RF41">RF41<a/> / `1.4` | RF |  Sim  | | | | | | EC05, EC11 | FT09, FT22 | US09 | ELOF41 |
| RNF01 / `1.4` | RNF | Não | | | P | | NFR02 | EC04, EC14 | FT07, FT30 | US38 | ELONF01 |
| RNF02 / `1.4` | RNF | Sim | | | C | | | EC06 | FT12 | US39 | ELONF02 |
| RNF03 / `1.4` | RNF | Sim | | | S | | NFR03 | EC06 | FT12 | US40 | ELONF03 |
| RNF04 / `1.4` | RNF | Não | | | U | | NFR01 | EC06, EC11, EC13 | FT13, FT24, FT28 | US41 | ELONF04 | 
| RNF05 / `1.4` | RNF | Sim | | | C | | | EC06 | FT12 | US39 | ELONF05 |
| RNF06 / `1.4` | RNF | Não | | | S | | | EC14 | FT29 | US38 | ELONF06 |
| RNF08 / `1.4` | RNF | Não | | | U | | NFR02 | EC11 | FT24 | US35 | ELONF08 |
| RNF09 / `1.4` | RNF | Não | | | U | | NFR01 | EC05, EC13 | FT10, FT27 | US36 | ELONF09 |
| RNF10 / `1.4` | RNF | Sim | | | C | | | EC06 | FT12 | US39 | ELONF10 |
| RNF11 / `1.4` | RNF | Sim | | | C | | | EC04 | FT07 | US06 | ELONF11 |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo">Victor Hugo</a>, 2025</p></font>

</center>

## Elos 

A tabela 2 mostra os elos entre os requisitos elicitados e os artefatos do projeto.
<center>

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Elos de rastreabilidade Forward-from</p></font>

| Elo | Requisito | Satisfação | Recusrso | Representação | Alocado | Agregação |
| --- | --------- | ---------- | -------- | ------------- | ------- | --------- |
| ELOF01 | RF01 | US01 | UC03 | ![](../assets/pos-rastreabilidade/foward/US01.jpg) | NFR02 | RF36 |
| ELOF02 | RF02 | US02 | UC02 | (../assets/pos-rastreabilidade/foward/US02.jpg) | NFR02 | RF37, RF38, RF39 |
| ELOF03 | RF03 | US03 | UC07 | | NRF03 | RF26, RF36 |
| ELOF04 | RF04 | US04 | UC08 | (../assets/pos-rastreabilidade/foward/US04.jpg) | NFR02 | RF25, RF27 |
| ELOF05 | RF05 | US05 | UC02 | (../assets/pos-rastreabilidade/foward/US05.jpg) | NRF03 | RF28 |
| ELOF06 | RF06 | US06 | UC10 | (../assets/pos-rastreabilidade/foward/US06.jpg) | NFR02 | RF01, RF03 |
| ELOF08 | RF08 | US07 | UC06 | | NFR02 | RF01, RF36 |
| ELOF09 | RF09 | US08 | UC08, UC09 | (../assets/pos-rastreabilidade/foward/US08.jpg) | NFR01 | RF21 |
| ELOF12 | RF12 | US09 | UC11 | (../assets/pos-rastreabilidade/foward/US09.jpg) | NFR02 | RF41 |
| ELOF13 | RF13 | US10 | UC08, UC10 | | NRF03 | RF04, RF25 |
| ELOF14 | RF14 | US11 | UC06, UC10 | | RNF03 | RF24 |
| ELOF15 | RF15 | US12 | UC10 | (../assets/pos-rastreabilidade/foward/US12.jpg) | NRF03 | RF10, RF26 |
| ELOF16 | RF16 | US13 | UC02, UC08 | | NFR01 | RF21 |
| ELOF17 | RF17 | US14 | UC01, UC03 | | NRF03 | RF10 |
| ELOF18 | RF18 | US15 | UC11 | | NRF03 | RF11 |
| ELOF20 | RF20 | US16 | UC01, UC06 | | NFR01 | RF29 |
| ELOF21 | RF21 | US17 | UC09, UC11 | | NFR01 | RF16, RF09 |
| ELOF23 | RF23 | US18 | UC02 | | NFR02 | RF02 |
| ELOF24 | RF24 | US19 | UC02, UC06 | | NFR02 | RF02, RF26 |
| ELOF25 | RF25 | US20 | UC09 | | NFR01 | RF04, RF27 |
| ELOF26 | RF26 | US21 | UC11 | (../assets/pos-rastreabilidade/foward/US21.jpg) | NRF03 | RF03, RF24 |
| ELOF27 | RF27 | US22 | UC08 | | NFR01 | RF04, RF25 |
| ELOF28 | RF28 | US23 | UC09, UC10 | | NRF03 | RF05 |
| ELOF29 | RF29 | US24 | UC01, UC03 | | NRF03 | RRF20 |
| ELOF31 | RF31 | US25 | UC02, UC06 | (../assets/pos-rastreabilidade/foward/US25.jpg) | NRF03 | RF17 |
| ELOF32 | RF32 | US26 | UC10, UC11 | (../assets/pos-rastreabilidade/foward/US26.jpg) | NFR02 | RF26 |
| ELOF33 | RF33 | US27 | UC01 | | NFR01 | RF34 |
| ELOF34 | RF34 | US28 | UC01 | (../assets/pos-rastreabilidade/foward/US28.jpg) | NFR01 | RF33 |
| ELOF35 | RF35 | US29 | UC06, UC08 | (../assets/pos-rastreabilidade/foward/US29.jpg) | NFR02 | RF02  |
| ELOF36 | RF36 | US30 | UC06, UC10 | | NFR01 | RF01, RF03 |
| ELOF37 | RF37 | US31 | UC02, UC19 | | NFR01 | RF02, RF24 |
| ELOF38 | RF38 | US32 | UC02, UC08 | | NFR01 | RF02 |
| ELOF39 | RF39 | US33 | UC09 | | NRF03 | RF02 |
| ELOF40 | RF40 | US34 | UC08, UC09 | | NFR01 | RF04 |
| ELOF41 | RF41 | US35 | UC01, UC06 | | NFR01 | RF12 |
| ELONF01 | RNF01 | ---- | ---- | | NFR03 | RNF03 |
| ELONF02 | RNF02 | US39 | UC01, UC06 | | NFR02 | RNF05, RNF10 |
| ELONF03 | RNF03 | US40 | UC11 | | NFR01 | RNF09 |
| ELONF04 | RNF04 | US37 | UC10, UC11 | | NFR01 | RNF03, RNF09 |
| ELONF05 | RNF05 | US39 | UC01, UC06 | | NFR02 | RNF02, RNF10 |
| ELONF06 | RNF06 | US38 | UC01, UC11 | | NFR01 | RNF03, RNF09 |
| ELONF08 | RNF08 | ---- | ---- | | NFR01 | RNF03, RNF04 |
| ELONF09 | RNF09 | US36 | UC11 | | NFR01 | RNF04, RNF03 |
| ELONF10 | RNF10 | US39 | UC01, UC06 | | NFR02 | RNF02, RNF05 |
| ELONF11 | RNF11 | ---- | ---- | | NFR03 | RNF10 |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/juliatakaki">Júlia Takaki</a>, 2025</p></font>

</center>

## Referência Bibliografia

> <a id="REF1">1.</a> Requirements Engineering Fundamentals. Disponível em: [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 12 jan. 2025.

> <a id="REF2">2.</a> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 12 jan. 2025.

## Bibliografia

> 1. Economia DF - "Rastreabilidade - Forward From". Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/forward_from/](https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/forward_from/). Acesso em: 12 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|12/01/2025|Criação e ajuste do Documento|[Victor Rodrigues](https://github.com/ViictorHugoo) e [Julia Takaki](https://github.com/juliatakaki)| |
