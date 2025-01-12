# Backward-From

## Introdução

Este artefato explora a utilização do método de rastreabilidade backward-from, uma abordagem essencial para o desenvolvimento de sistemas que busca conectar requisitos às suas fontes. A rastreabilidade de requisitos é uma prática fundamental que viabiliza o acompanhamento dos requisitos desde sua concepção até sua implementação, proporcionando maior clareza sobre sua origem e impacto. Isso contribui para a gestão eficiente de mudanças, garantia da qualidade e alinhamento contínuo com as expectativas dos stakeholders.

O método backward-from enfatiza a criação de vínculos claros entre cada requisito e sua fonte original, como solicitações de clientes, processos de negócios ou outras referências relevantes. Para fortalecer essa abordagem, utilizamos recursos como os [slides da aula 26](#REF1) ministrada pela professora Milene Serrano e o livro [Requirements Engineering Fundamentals](#REF2), de Klaus Pohl e Chris Rupp, que fornecem diretrizes valiosas para uma rastreabilidade estruturada e completa.

Uma rastreabilidade bem implementada não apenas facilita a validação e verificação dos sistemas, mas também ajuda a identificar problemas antecipadamente, economizando recursos e otimizando o processo de desenvolvimento. Além disso, garante que o sistema final corresponda com precisão às necessidades do cliente, promovendo confiança e satisfação ao longo de todo o ciclo de vida do sistema.

## Metodologia

A abordagem de rastreabilidade de requisitos desenvolvida por Toranzo desempenha um papel central no processo de desenvolvimento de software, garantindo que os requisitos possam ser acompanhados em todas as etapas do ciclo de vida do projeto, desde a concepção inicial até a entrega final do produto.

Na aplicação do método backward-from, é utilizado o meta-modelo proposto por Toranzo, que organiza os requisitos identificados em diferentes níveis e elos. De acordo com os slides 19 da [aula 26](#REF1) ministrada pela professora Milene Serrano, os níveis são definidos da seguinte forma:

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

Para estruturar a criação do meta-modelo de Toranzo, foram desenvolvidas as **tabelas 1 e 2**, que categorizam os requisitos em funcionais (RF) e não-funcionais (RNF).

## Tabelas de requisitos funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos funcionais, que está sendo demonstrado na tabela 1 a seguir:

**Legendas:**
> - BCFx: Requisitos do Backward-From número x
> - RFx: Requisito Funcional número x
> - BFx: Requisito Funcinal do Brainstorm número x;
> - GFx: Requisito do Grupo de Foco número x;
> - IS: Requisito da Introspecção número x;
> - GLOx: Requisito do Glossário número x;


<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos funcionais elicitados</p></font>
</div>

| ID    | Código | Descrição                                                                            | Implementado | Rastreabilidade |
| ----- | ------ | ------------------------------------------------------------------------------------ | ------------ | --------------- |
| BCF01 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF01">RF01 </a>    | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis com suas características principais: nome do título, rentabilidade, valor mínimo e vencimento.                                                                                                                                                                              | Sim          | [IT1](./introspeccao.md), [GLO01](./glossario.md) |
| BCF02 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF02">RF02 </a>    | O sistema deverá permitir a simulação de investimento nos títulos SELIC, Prefixado e Inflação                                                                                                                                                                                                                                                                       | Sim          | [IT2](./introspeccao.md)                          |
| BCF03 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF03">RF03 </a>    | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada.	                                                                                                                                                                                                         | Sim          | [IT3](./introspeccao.md), [GLO07](./glossario.md) |
| BCF04 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF04">RF04 </a>    | Oferecer funcionalidade para salvar metas de investimentos (Sonhos).                                                                                                                                                                                                                                                                                                | Sim          | [IT4](./introspeccao.md)                          |
| BCF05 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF05">RF05 </a>    | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria.                                                                                                                                                                                                                                                                       | Sim          | [IT5](./introspeccao.md)                          |
| BCF06 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF06">RF06 </a>    | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira.                                                                                                                                                                                                                                                                 | Sim          | [IT6](./introspeccao.md)                          |
| BCF07 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF08">RF08 </a>    | Permitir a consulta de operações de compra de títulos do tesouro nacional realizadas e agendadas na aplicação.                                                                                                                                                                                                                                                      | Sim          | [IT8](./introspeccao.md)                          |
| BCF08 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF09">RF09 </a>    | O aplicativo deverá possuir uma tela intitulada “Fale Conosco” com informações de contato e perguntas frequentes dos usuários.                                                                                                                                                                                                                                      | Sim          | [IT9](./introspeccao.md)                          |
| BCF09 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF12">RF12 </a>    | Permitir a visualização dos dados cadastrais do usuário (nome, cpf, email, celular).                                                                                                                                                                                                                                                                                | Sim          | [IT12](./introspeccao.md)                         |
| BCF10 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF13">RF13 </a>    | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos.                                                                                                                                                                                                                                                                   | Não          | [IT13](./introspeccao.md), [GLO07](./glossario.md)|
| BCF11 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF14">RF14 </a>    | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos.                                                                                                                                                                                                                                                                 | Não          | [IT14](./introspeccao.md)                         |
| BCF12 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF15">RF15 </a>    | O sistema deve fornecer relatórios mensais contendo a evolução dos rendimentos dos títulos adquiridos pelo usuário com base nos meses anteriores.                                                                                                                                                                                                                   | Não          | [IT15](./introspeccao.md)                         |
| BCF13 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF16">RF16 </a>    | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto.                                                                                                                                                                                                                                                                     | Não          | [IT16](./introspeccao.md), [BF10](./brainstorm.md)|
| BCF14 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF17">RF17 </a>    | Oferecer integração com carteiras digitais de outros bancos digitais para pagamento direto de investimentos. Atualmente as instituições financeiras integradas são “INTER DTVM LTDA”, “NU INVEST CORRETORA DE VALORES S.A” e “XP INVESTIMENTOS CCTVM S/A”                                                                                                           | Não          | [IT17](./introspeccao.md)                         |
| BCF15 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF18">RF18 </a>    | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação.                                                                                                                                                                                                                                                                                       | Não          | [IT18](./introspeccao.md)                         |
| BCF16 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF20">RF20 </a>    | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente) durante o seu cadastro no sistema.                                                                                                                                                                                                                          | Não          | [BF1](./brainstorm.md)                            |
| BCF17 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF21">RF21 </a>    | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades.                                                                                                                                                                                                                                                                             | Não          | [BF2](./brainstorm.md)                            |
| BCF18 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF23">RF23 </a>    | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação.                                                                                                                                                                                                                                                                                   | Não          | [BF4](./brainstorm.md)                            |
| BCF19 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF24">RF24 </a>    | O sistema deverá disponibilizar uma ferramenta para simular a evolução do investimento em um título do tesouro nacional em comparação com outras opções de investimento como a poupança, LCI (Letra de Crédito Imobiliário) e LCA (Letra de Crédito do Agronegócio), Fundo de Renda Fixa Referenciado DI e CDB (Certificado de Depósito Bancário).                  | Sim          | [BF5](./brainstorm.md), [GF04](./grupo-de-foco.md)|
| BCF20 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF25">RF25 </a>    | A tela de metas e sonhos deverá ser capaz de simular a evolução das metas                                                                                                                                                                                                                                                                                           | Não          | [BF7](./brainstorm.md)                            |
| BCF21 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF26">RF26 </a>    | O aplicativo deve apresentar um dashboard com dados de rentabilidade dos títulos adquiridos e taxa de inflação.                                                                                                                                                                                                                                                     | Não          | [BF8](./brainstorm.md)                            |
| BCF22 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF27">RF27 </a>    | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos".                                                                                                                                                                                                                                                                                                 | Não          | [BF12](./brainstorm.md)                           |
| BCF23 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF28">RF28 </a>    | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos".                                                                                                                                                                                                                                                                                                 | Não          | [BF14](./brainstorm.md)                           |
| BCF24 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF29">RF29 </a>    | O sistema deve exibir sugestões personalizadas com base na expertise declarada pelo usuário na página inicial do "Meu Investimento".                                                                                                                                                                                                                                | Não          | [BF15](./brainstorm.md)                           |
| BCF25 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF31">RF31 </a>    | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento.                                                                                                                                                                                                                                                               | Sim          | [GLO02](./glossario.md)                           |
| BCF26 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF32">RF32 </a>    | 	O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário.                                                                                                                                                                                                                                                                             | Sim          | [GLO03](./glossario.md)                           |
| BCF27 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF33">RF33 </a>    | 	O aplicativo deverá permitir que o usuário faça cadastro na aplicação criando uma conta própria no sistema.                                                                                                                                                                                                                                                        | Não          | [GF02](./grupo-de-foco.md)                        |
| BCF28 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF34">RF34 </a>    | O aplicativo deverá possuir a opção de realizar o login e cadastro a partir do sistema gov.br                                                                                                                                                                                                                                                                       | Sim          | [GF01](./grupo-de-foco.md)                        |
| BCF29 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF35">RF35 </a>    | Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois                                                                                                                                                                                                                                             | Sim          | [IT21](./introspeccao.md)                         |
| BCF30 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF36">RF36 </a>    | Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois                                                                                                                                                                                                                                             | Sim          | [IT01](./introspeccao.md), [GLO01](./glossario.md)|
| BCF31 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF37">RF37 </a>    | O sistema deverá possuir um simulador da evolução de um título do tesouro direto com base em um determinado período de tempo                                                                                                                                                                                                                                        | Sim          | [IT7](./introspeccao.md)                          |
| BCF32 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF38">RF38 </a>    | O simulador deverá possuir um questionário para obter do usuário as informações necessárias para gerar o simulador.                                                                                                                                                                                                                                                 | Sim          | [IT26](./introspeccao.md)                         |
| BCF33 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF39">RF39 </a>    | O simulador deverá possuir as informações de: título do tesouro nacional que será usado, tempo de investimento e valor que será resgatado no futuro ou valor que será investido agora.                                                                                                                                                                              | Sim          | [IT27](./introspeccao.md)                         |
| BCF34 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF40">RF40 </a>    | Cada meta deve possuir uma barra de progresso representando o progresso individual de conclusão da meta.                                                                                                                                                                                                                                                            | Não          | [BF12](./brainstorm.md)                           |
| BCF35 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RF41">RF41 </a>    | As contas cadastradas na aplicação deverão possuir os dados de nome, cpf, email e celular do dono da conta.                                                                                                                                                                                                                                                         | Sim          | [GF02](./grupo-de-foco.md)                        |

<div align="center">
<font size="3"><p style="text-align: center">Autores: <a href="https://github.com/moonshinerd">Víctor Schmidt</a> e <a href="https://github.com/thaleseuflauzino">Thales Euflauzino</a>, 2025</p></font>
</div>

## Tabelas de requisitos não-funcionais

Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na tabela 2 a seguir:

**Legendas:**

> - BCFx: Requisitos do Backward-From número x
> - RNFx: Requisito Não Funcional número x
> - BFNx: Requisito Não Funcional do Brainstorm número x;
> - GFx: Requisito do Grupo de Foco número x;
> - IS: Requisito da Introspecção número x;
> - GLOx: Requisito do Glossário número x;


<center>

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Requisitos não-funcionais elicitados</p></font>

| ID    | Código | Descrição                                                                            | Implementado | Rastreabilidade |
| ----- | ------ | ------------------------------------------------------------------------------------ | ------------ | --------------- |
| BCF36 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF01">RNF01 </a>    | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas.                                                                               | Não          | [IT20](./introspeccao.md)                                                                                |
| BCF37 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF02">RNF02 </a>    | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD.                                                                                             | Sim          | [IT21](./introspeccao.md), [GF06](./grupo-de-foco.md)                                                    |
| BCF38 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF03">RNF03 </a>    | O aplicativo deve ser responsivo para dispositivos móveis e tablets.                                                                                             | Sim          | [IT22](./introspeccao.md), [GF07](./grupo-de-foco.md), [GLO08](./glossario.md)                           |
| BCF39 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF04">RNF04 </a>    | A interface do aplicativo deve seguir as diretrizes de acessibilidade da norma técnica [NBR 17060:2022](HTTPS://WWW.ABNTCOLECAO.COM.BR/MPF/NORMA.ASPX?ID=516652#)| Não          | [IT23](./introspeccao.md), [BFN11](./brainstorm.md), [GF08](./grupo-de-foco.md), [GLO04](./glossario.md) |
| BCF40 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF05">RNF05 </a>    | O sistema deve permitir integrações seguras com APIs de instituições financeiras respeitando as normas da LGPD.                                                  | Sim          | [IT24](./introspeccao.md), [GLO06](./glossario.md)                                                       |
| BCF41 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF06">RNF06 </a>    | O aplicativo deverá disponibilizar suporte para múltiplos idiomas (português como padrão).                                                                       | Não          | [IT25](./introspeccao.md)                                                                                |
| BCF42 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF08">RNF08 </a>    | O perfil de recomendação de investimentos deve ser acessível a partir de 3 cliques de qualquer parte do aplicativo.                                              | Não          | [BFN9](./brainstorm.md)                                                                                  |
| BCF43 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF09">RNF09 </a>    | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário.                                                                       | Não          | [BFN13](./brainstorm.md)                                                                                 |
| BCF44 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF10">RNF10 </a>    | O sistema deverá garantir a segurança nas transações de títulos públicos.                                                                                        | Sim          | [GLO02](./glossario.md)                                                                                  |
| BCF45 | <a href="../../elicitacao/grupo5/requisitos/#anchor_RNF11">RNF11 </a>    | Os títulos do tesouro nacional deverão estar sempre atualizados com relação a inflação e a taxa de juros.                                                        | Sim          | [GLO03](./glossario.md)                                                                                  |

<font size="3"><p style="text-align: center">Autores: <a href="https://github.com/moonshinerd">Víctor Schmidt</a> e <a href="https://github.com/thaleseuflauzino">Thales Euflauzino</a>, 2025</p></font>

</center>

## Elos

Neste trecho, exploramos os vínculos associados aos requisitos listados nas tabelas 1 e 2. Conforme a metodologia apresentada, cada requisito será classificado de acordo com seu tipo de vínculo. Vale destacar que todos os requisitos identificados estão inseridos na categoria de Desenvolvimento, ou seja, têm origem em artefatos gerados durante o processo de criação do projeto. Esses requisitos não possuem conexão direta com aspectos organizacionais ou gerenciais. A partir dessa análise, foi elaborada a tabela 3, que detalha os vínculos (elos) relacionados a esses requisitos.


<center>

#### **Tabela 3:** Elos de rastreabilidade

| ID      | Requisitos  | Tipo de elo     | Descrição do elo |
|---------|-------------|-----------------|------------------------------------------------|
| ELOB01  | BCF01       | Representação                 | O requisito está relacionado à forma como as informações sobre títulos públicos (nome, rentabilidade, valor mínimo e vencimento) são exibidas ao usuário. |
| ELOB02  | BCF02       | Satisfação                    | Este requisito depende de simulações precisas de investimento nos diferentes tipos de títulos (SELIC, Prefixado e Inflação) para atender às expectativas do usuário.|
| ELOB03  | BCF03       | Agregação                     | Relaciona-se ao cálculo de valores líquidos com base em dados de resgate antecipado e rentabilidade acumulada, que dependem de múltiplas variáveis, como data e taxa acumulada.                    |
| ELOB04  | BCF04       | Representação                 | Este elo trata de como as metas de investimento (Sonhos) serão representadas no sistema, permitindo ao usuário salvar seus objetivos financeiros.                      |
| ELOB05  | BCF05       | Alocado                       | Refere-se à funcionalidade de planejamento de aposentadoria, que deve ser vinculada a um subsistema específico responsável por processar dados como ano esperado de aposentadoria e simulações relacionadas.        |
| ELOB06  | BCF06       | Recurso                       | Este requisito depende de dados externos, como a taxa de custódia da B3 e a taxa de administração da instituição financeira, sendo essencial que o sistema tenha acesso a essas informações para exibição ao usuário.        |
| ELOB07  | BCF07       | Representação                 | Relaciona-se à forma como as operações de compra e agendamento de títulos do Tesouro Nacional serão exibidas e organizadas para consulta dentro do aplicativo.        |
| ELOB08  | BCF08       | Responsabilidade              | O requisito envolve a criação de uma tela “Fale Conosco”, que é uma responsabilidade da equipe de suporte ao cliente, incluindo informações de contato e perguntas frequentes.                     |
| ELOB09  | BCF09       | Representação                 | Este elo trata de como os dados cadastrais do usuário (nome, CPF, e-mail, celular) serão exibidos de forma clara e acessível no sistema.                 |
| ELOB10  | BCF10       | Satisfação e Responsabilidade | A implementação de notificações personalizadas depende tanto da responsabilidade de uma funcionalidade específica quanto da satisfação do usuário em ser lembrado de metas ou vencimentos de títulos.                  |
| ELOB11  | BCF11       | Alocado                       | O requisito de transferência automática entre investimentos é alocado a subsistemas específicos que gerenciam metas financeiras e execução automatizada de operações.                   |
| ELOB12  | BCF12       | Satisfação                    | O fornecimento de relatórios mensais satisfaz a necessidade do usuário de monitorar e entender a evolução de seus rendimentos financeiros.                         |
| ELOB13  | BCF13       | Representação                 | O recurso educativo é representado por vídeos e artigos, que são formatos de entrega acessíveis e compreensíveis para os usuários.          |
| ELOB14  | BCF14       | Integração                    | Relaciona-se à agregação de carteiras digitais de terceiros para possibilitar pagamentos diretos no aplicativo, representando a interoperabilidade entre sistemas financeiros.              |
| ELOB15  | BCF15       | Monitoramento                 | Incorporar alertas de mercado é uma funcionalidade alocada ao sistema de notificações e depende de recursos externos para obter dados em tempo real sobre a SELIC ou inflação.                     |
| ELOB16  | BCF16       | Responsabilidade              | A personalização do perfil do usuário por expertise é responsabilidade do módulo de cadastro e preferências, que deve garantir que os dados sejam capturados corretamente para ajustar a experiência do usuário.                 |
| ELOB17  | BCF17       | Representação                 | O tutorial guia o usuário no uso do aplicativo, sendo representado por uma sequência de telas ou mensagens interativas que orientam sobre as funcionalidades disponíveis.                  |
| ELOB18  | BCF18       | Representação                 | A exibição da liquidez dos títulos é representada como informações numéricas ou visuais durante as simulações financeiras, facilitando a compreensão do usuário.                    |
| ELOB19  | BCF19       | Recurso                       | A comparação entre diferentes investimentos utiliza recursos de cálculo e análise baseados em dados históricos e projeções, permitindo ao sistema gerar insights confiáveis para o usuário.                          |
| ELOB20  | BCF20       | Representação                 | A evolução das metas é representada de forma gráfica e interativa na tela de metas e sonhos, proporcionando ao usuário uma visualização clara do progresso de seus objetivos financeiros.            |
| ELOB21  | BCF21       | Representação                 | O dashboard é representado visualmente por gráficos e tabelas que exibem dados de rentabilidade dos títulos adquiridos e a taxa de inflação.             |
| ELOB22  | BCF22       | Representação                 | A barra de progresso na aba "Meus Sonhos" é uma representação visual do progresso em direção às metas financeiras do usuário, permitindo fácil monitoramento.                  |
| ELOB23  | BCF23       | Representação                 | Similar ao requisito anterior, a barra de progresso é representada visualmente, reforçando a experiência interativa do usuário ao acompanhar seus sonhos e metas.                |
| ELOB24  | BCF24       | Personalização                | As sugestões personalizadas dependem da autodeclaração de expertise do usuário e são exibidas dinamicamente na página inicial do "Meu Investimento", adaptando-se ao perfil do usuário.                               |
| ELOB25  | BCF25       | Recurso                       | A compra de títulos públicos utiliza diferentes métodos de pagamento, representando uma dependência de recursos externos, como integração com APIs de pagamento ou bancos parceiros.                  |
| ELOB26  | BCF26       | Alocado                       | A exibição da rentabilidade acumulada de cada título é alocada ao módulo de análise financeira, que calcula e apresenta essas informações para o usuário.                  |
| ELOB27  | BCF27       | Responsabilidade              | O cadastro de contas próprias é uma responsabilidade do módulo de autenticação do sistema, que gerencia os dados de login e segurança dos usuários.           |
| ELOB28  | BCF28       | Integração                    | A funcionalidade de login e cadastro via gov.br integra o sistema com a plataforma gov.br, reforçando a autenticação e possibilitando o uso de credenciais governamentais existentes.           |
| ELOB29  | BCF29       | Personalização                | A funcionalidade de escolha de investimentos, definição de valores e decisão sobre investir agora ou depois reflete a personalização das ações do usuário, conectada às preferências declaradas no momento do uso.                  |
| ELOB30  | BCF30       | Representação                 | As opções de escolha de investimentos, definição de valores e decisões de investimento são representadas por botões e campos de entrada no sistema, com suporte a terminologias claras explicadas no glossário associado.                    |
| ELOB31  | BCF31       | Representação                 | O simulador de evolução de um título do tesouro direto é representado por gráficos interativos que mostram a projeção de valores com base em um período de tempo selecionado pelo usuário.                          |
| ELOB32  | BCF32       | Recurso                       | O questionário é um recurso essencial para coletar informações do usuário (como perfil de investimento e objetivos) e gerar os resultados personalizados do simulador.            |
| ELOB33  | BCF33       | Representação                 | O simulador exibe informações como título selecionado, tempo de investimento, valor futuro esperado ou valor investido atualmente, representando essas variáveis nos cálculos exibidos ao usuário.              |
| ELOB34  | BCF34       | Representação                 | A barra de progresso para cada meta é uma representação visual que reflete o avanço individual na conclusão das metas definidas pelo usuário, facilitando o acompanhamento.                      |
| ELOB35  | BCF35       | Responsabilidade              | A gestão de dados das contas (nome, CPF, e-mail e celular) é uma responsabilidade do módulo de cadastro e autenticação, que garante a segurança e integridade dessas informações.                 |
| ELOB36  | BCF36       | Qualidade                     | O tempo de resposta inferior a 2 segundos para consultas básicas garante a qualidade do desempenho do sistema, proporcionando uma experiência fluida ao usuário.                  |
| ELOB37  | BCF37       | Responsabilidade              | Garantir a segurança dos dados sensíveis é uma responsabilidade essencial para atender à LGPD, protegendo a privacidade do usuário e evitando vazamentos de informações.                    |
| ELOB38  | BCF38       | Qualidade                     | A responsividade do aplicativo assegura que ele funcione de maneira adequada em dispositivos móveis e tablets, atendendo a uma ampla variedade de usuários e dispositivos.                          |
| ELOB39  | BCF39       | Conformidade                  | Seguir as diretrizes de acessibilidade da norma técnica [NBR 17060:2022](HTTPS://WWW.ABNTCOLECAO.COM.BR/MPF/NORMA.ASPX?ID=516652#) assegura que o aplicativo atenda a padrões de acessibilidade e usabilidade para todos os públicos.            |
| ELOB40  | BCF40       | Recurso                       | A integração segura com APIs financeiras é um recurso fundamental para possibilitar transações e troca de informações sensíveis, respeitando a LGPD.              |
| ELOB41  | BCF41       | Funcionalidade                | O suporte para múltiplos idiomas (com português como padrão) é uma funcionalidade que aumenta a acessibilidade e torna o aplicativo útil para um público mais diversificado.                  |
| ELOB42  | BCF42       | Usabilidade                   | A acessibilidade do perfil de recomendação em até 3 cliques melhora a usabilidade do aplicativo, permitindo que o usuário navegue rapidamente até a funcionalidade desejada.                |
| ELOB43  | BCF43       | Experiência                   | A inclusão de um tema escuro melhora a experiência do usuário, especialmente em ambientes com pouca iluminação, oferecendo uma interface mais confortável e personalizada.                                 |
| ELOB44  | BCF44       | Responsabilidade              | Garantir a segurança nas transações de títulos públicos é uma responsabilidade crítica para proteger os investimentos do usuário contra fraudes e acessos não autorizados.                  |
| ELOB45  | BCF45       | Conformidade                  | Manter os títulos do Tesouro Nacional atualizados com relação à inflação e taxa de juros é uma conformidade necessária para assegurar que os cálculos e informações fornecidas sejam precisos e confiáveis.                  |

<font size="3"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a>, 2025</p></font>

</center>

### Tipos de Elos
1. **Representação**  
   Refere-se à maneira como as informações são exibidas ou organizadas no sistema. Esse tipo de elo garante que os dados sejam apresentados de forma clara, acessível e amigável ao usuário. Exemplos incluem gráficos, tabelas, barras de progresso ou elementos interativos.

2. **Satisfação**  
   Relaciona-se ao atendimento das expectativas e necessidades dos usuários. Esse elo assegura que as funcionalidades forneçam uma experiência positiva, como a personalização de notificações ou relatórios que atendem aos desejos dos stakeholders.

3. **Agregação**  
   Este elo representa a combinação de diferentes dados ou variáveis para fornecer uma informação consolidada. Por exemplo, cálculos que utilizam múltiplos inputs, como taxas e datas, para gerar valores acumulados.

4. **Alocado**  
   Define onde uma funcionalidade ou requisito está posicionado no sistema. Este elo está relacionado à organização de módulos ou subsistemas específicos responsáveis por determinadas tarefas, como planejamento financeiro ou análise de dados.

5. **Recurso**  
   Relaciona-se à dependência de dados externos ou serviços adicionais para o funcionamento de uma funcionalidade. Exemplo: integração com APIs financeiras, uso de taxas externas ou coleta de informações para simulações.

6. **Responsabilidade**  
   Indica quais partes do sistema ou equipes são responsáveis por implementar ou manter uma funcionalidade específica, como o módulo de suporte ou cadastro. É essencial para o gerenciamento de responsabilidades internas.

7. **Integração**  
   Este elo aborda a interoperabilidade entre sistemas ou subsistemas. Garante que funcionalidades, como o login com gov.br ou carteiras digitais, funcionem de forma harmoniosa com outras plataformas.

8. **Personalização**  
   Refere-se à adaptação de funcionalidades com base nas preferências, perfil ou escolhas do usuário. Esse elo torna o sistema mais relevante para o usuário individual, como sugestões dinâmicas ou exibição personalizada de informações.

9. **Monitoramento**  
   Envolve o acompanhamento de eventos ou dados em tempo real, como alertas de mercado ou mudanças em taxas. Esse elo é crucial para manter o usuário informado sobre situações relevantes.

10. **Qualidade**  
   Focado na performance e experiência geral do sistema. Exemplos incluem tempos de resposta rápidos, responsividade para dispositivos móveis e entrega de informações precisas e confiáveis.

11. **Conformidade**  
   Garante que o sistema esteja alinhado a normas e regulamentações externas, como acessibilidade ou proteção de dados sensíveis (LGPD). É essencial para manter o aplicativo em conformidade legal.

12. **Funcionalidade**  
   Refere-se aos recursos ou capacidades do sistema que melhoram a experiência geral do usuário, como suporte a múltiplos idiomas ou temas. Esse elo contribui diretamente para a utilidade do aplicativo.

13. **Usabilidade**  
   Relaciona-se à facilidade de uso do sistema, como navegação intuitiva ou simplificação de cliques para acessar funcionalidades importantes. É um elo fundamental para a satisfação do usuário.

14. **Experiência**  
   Este elo aborda melhorias subjetivas, como a introdução de um tema escuro, que tornam a interação do usuário mais confortável e atraente.

Cada tipo de elo é projetado para garantir que os requisitos do sistema sejam coerentes, alinhados com os objetivos do projeto e otimizados para oferecer a melhor experiência possível ao usuário.

## Conclusão

Tomando o Meta-modelo de Toranzo como base, este documento descreve 45 elos de rastreabilidade que possibilitam avaliar a coerência e a qualidade dos requisitos identificados para o projeto do aplicativo Tesouro Direto. Esses elos abrangem diversos níveis de abstração e dimensões dos requisitos, além de suas inter-relações. Dessa forma, torna-se viável verificar se os requisitos estão alinhados aos objetivos do projeto, se atendem às expectativas e necessidades dos stakeholders, e se apresentam consistência e completude.


## Referência Bibliografia

> <a id="REF1">1.</a> Requirements Engineering Fundamentals. Disponível [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 12 jan. 2025.

> <a id="REF2">2.</a> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 12 jan. 2025.

## Bibliografia

> 1. Economia DF - "Rastreabilidade - Backward From". Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/backward_from/](https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/backward_from/). Acesso em: 12 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|12/01/2025|Criação e ajuste do Documento|[Víctor Schmidt](https://github.com/moonshinerd)||
|`1.1`|12/01/2025|Configurando artefato e adicionando os requisitos que trabalhamos na disciplina|[Grupo](../../)| [Víctor Schmidt](https://github.com/moonshinerd) e [Thales Euflauzino](https://github.com/thaleseuflauzino) |
|`1.2`|12/01/2025|Revisando ortografia dos textos|[Júlia Takaki](https://github.com/juliatakaki)|
