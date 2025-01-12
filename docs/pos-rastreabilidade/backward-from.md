# Backward-From

## Introdução

Este artegato explora a utilização do método de rastreabilidade backward-from, uma abordagem essencial para o desenvolvimento de sistemas que busca conectar requisitos às suas fontes. A rastreabilidade de requisitos é uma prática fundamental que viabiliza o acompanhamento dos requisitos desde sua concepção até sua implementação, proporcionando maior clareza sobre sua origem e impacto. Isso contribui para a gestão eficiente de mudanças, garantia da qualidade e alinhamento contínuo com as expectativas dos stakeholders.

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

<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Elos de rastreabilidade.</p></font>

| ID      | Requisitos  | Tipo de elo     | Descrição do elo |
|---------|-------------|-----------------|------------------------------------------------|
| ELOB01  | BCF01       | Representação   | O requisito está relacionado à forma como as informações sobre títulos públicos (nome, rentabilidade, valor mínimo e vencimento) são exibidas ao usuário. |
| ELOB02  | BCF02       | Representação   |                                    |
| ELOB03  | BCF03       | Representação   |                     |
| ELOB04  | BCF04       | Representação   |                       |
| ELOB05  | BCF05       | Satisfação      | atende às necessidades.        |
| ELOB06  | BCF06       | Satisfação      | atende às necessidades.        |
| ELOB07  | BCF07       | Satisfação      | atende às necessidades.        |
| ELOB08  | BCF08       | Satisfação      |                      |
| ELOB09  | BCF09       | Satisfação      |                  |
| ELOB10  | BCF10       | Satisfação      | O requisito RF10, que diz que o aplicativo deve permitir pagamentos de débitos por cartão, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB11  | BCF11       | Satisfação      | O requisito RF11, que diz que o aplicativo deve permitir pagamentos de débitos por PIX, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                    |
| ELOB12  | BCF12       | Satisfação      | O requisito RF12, que diz que o aplicativo deve permitir parcelamento de débitos, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                          |
| ELOB13  | BCF13       | Satisfação      | O requisito RF13, que diz que o aplicativo deve consultar o histórico de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.            |
| ELOB14  | BCF14       | Satisfação      | O requisito RF14, que diz que o aplicativo deve consultar o extrato de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.              |
| ELOB15  | BCF15       | Satisfação      | O requisito RF15, que diz que o aplicativo deve consultar débitos de forma integrada, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                      |
| ELOB16  | BCF16       | Satisfação      | O requisito RF16, que diz que o aplicativo deve permitir pagamentos de débitos por boleto, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                 |
| ELOB17  | BCF17       | Satisfação      | O requisito RF17, que diz que o aplicativo deve permitir pagamentos de débitos por cartão, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB18  | BCF18       | Satisfação      | O requisito RF18, que diz que o aplicativo deve permitir pagamentos de débitos por PIX, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                    |
| ELOB19  | BCF19       | Satisfação      | O requisito RF19, que diz que o aplicativo deve permitir parcelamento de débitos, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                          |
| ELOB20  | BCF20       | Satisfação      | O requisito RF20, que diz que o aplicativo deve consultar o histórico de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.            |
| ELOB21  | BCF21       | Satisfação      | O requisito RF21, que diz que o aplicativo deve consultar o extrato de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.              |
| ELOB22  | BCF22       | Satisfação      | O requisito RF22, que diz que o aplicativo deve consultar o saldo do programa Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB23  | BCF23       | Satisfação      | O requisito RF23, que diz que o aplicativo deve consultar o extrato do programa Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                |
| ELOB24  | BCF24       | Representação   | O requisito RF25, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é representação, pois captura a forma dos requisitos.                                 |
| ELOB25  | BCF25       | Satisfação      | O requisito RF26, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB26  | BCF26       | Satisfação      | O requisito RF30, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB27  | BCF27       | Recurso         | O requisito RNF24, que diz que o aplicativo deve ter uma interface amigável, tem como fonte a necessidade do usuário. O tipo de elo é recurso, pois expressa como o requisito contribui para a disponibilidade de um recurso.           |
| ELOB28  | BCF28       | Recurso         | O requisito RNF25, que diz que o aplicativo deve ser seguro, tem fonte a necessidade do usuário. O tipo de elo é recurso, pois expressa como o requisito contribui para a disponibilidade de um recurso.           |
| ELOB29  | BCF29       | Satisfação      | O requisito RF10, que diz que o aplicativo deve permitir pagamentos de débitos por cartão, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB30  | BCF30       | Satisfação      | O requisito RF11, que diz que o aplicativo deve permitir pagamentos de débitos por PIX, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                    |
| ELOB31  | BCF31       | Satisfação      | O requisito RF12, que diz que o aplicativo deve permitir parcelamento de débitos, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                          |
| ELOB32  | BCF32       | Satisfação      | O requisito RF13, que diz que o aplicativo deve consultar o histórico de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.            |
| ELOB33  | BCF33       | Satisfação      | O requisito RF14, que diz que o aplicativo deve consultar o extrato de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.              |
| ELOB34  | BCF34       | Satisfação      | O requisito RF15, que diz que o aplicativo deve consultar débitos de forma integrada, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                      |
| ELOB35  | BCF35       | Satisfação      | O requisito RF16, que diz que o aplicativo deve permitir pagamentos de débitos por boleto, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                 |
| ELOB36  | BCF36       | Satisfação      | O requisito RF17, que diz que o aplicativo deve permitir pagamentos de débitos por cartão, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB37  | BCF37       | Satisfação      | O requisito RF18, que diz que o aplicativo deve permitir pagamentos de débitos por PIX, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                    |
| ELOB38  | BCF38       | Satisfação      | O requisito RF19, que diz que o aplicativo deve permitir parcelamento de débitos, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                          |
| ELOB39  | BCF39       | Satisfação      | O requisito RF20, que diz que o aplicativo deve consultar o histórico de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.            |
| ELOB40  | BCF40       | Satisfação      | O requisito RF21, que diz que o aplicativo deve consultar o extrato de pagamentos realizados, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.              |
| ELOB41  | BCF41       | Satisfação      | O requisito RF22, que diz que o aplicativo deve consultar o saldo do programa Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB42  | BCF42       | Satisfação      | O requisito RF23, que diz que o aplicativo deve consultar o extrato do programa Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                |
| ELOB43  | BCF43       | Representação   | O requisito RF25, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é representação, pois captura a forma dos requisitos.                                 |
| ELOB44  | BCF44       | Satisfação      | O requisito RF26, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |
| ELOB45  | BCF45       | Satisfação      | O requisito RF30, que diz que o aplicativo deve permitir pagamentos por saldo Nota Legal, tem como fonte a necessidade do usuário. O tipo de elo é satisfação, pois expressa como o requisito atende às necessidades.                  |

<font size="3"><p style="text-align: center">Autores: <a href="https://github.com/gabrielrosa09">Gabriel Rosa</a> e <a href="https://github.com/LucasOliveiraDiasMarquesFerreira">Lucas Oliveira</a>, 2023</p></font>

</center>

## Conclusão

Considerando o Meta-modelo de Toranzo como referência, este documento apresenta 30 elos de rastreabilidade que permitem avaliar a qualidade e a coerência dos requisitos elicitados para o projeto do aplicativo do Economia-Df. Esses elos abrangem as diferentes dimensões e níveis de abstração dos requisitos, bem como as relações entre eles. Assim, é possível verificar se os requisitos atendem às necessidades e expectativas dos stakeholders, se são consistentes e completos, e se estão alinhados com os objetivos do projeto.


## Referência Bibliografia

> <a id="REF1">1.</a> Requirements Engineering Fundamentals. Disponível [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 12 jan. 2025.

> <a id="REF2">2.</a> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 12 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|12/01/2025|Criação e ajuste do Documento|[Víctor Schmidt](https://github.com/moonshinerd)||
