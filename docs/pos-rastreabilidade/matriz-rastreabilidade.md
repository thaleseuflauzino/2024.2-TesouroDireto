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
| RF01 | RF | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis com suas características principais: nome do título, rentabilidade, valor mínimo e vencimento. | IT1, GLO01 | Sim | Caso de Uso, Léxicos, Backlog, História de Usuário | ELOB01, ELOF01 |
| RF02 | RF | O sistema deverá permitir a simulação de investimento nos títulos SELIC, Prefixado e Inflação | IT2 | Sim | Caso de Uso, Cenários, Léxicos, Backlog, História de Usuário | ELOB02, ELOF02 |
| RF03 | RF | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada. | IT3, GLO07 | Sim | Caso de Uso, Cenários, Backlog, História de Usuário | ELOB03, ELOF03 |
| RF04 | RF | Oferecer funcionalidade para salvar metas de investimentos (Sonhos). | IT4 | Sim | Caso de Uso, Cenários, Backlog, História de Usuário | ELOB04, ELOF04 |
| RF05 | RF | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria. | IT5 | Sim | Cenários, Backlog, História de Usuário | ELOB05, ELOF05 |
| RF06 | RF | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | IT6 | Sim | Léxicos, Backlog, História de Usuário | ELOB06, ELOF06 |
| RF08 | RF | Permitir a consulta de operações de compra de títulos do tesouro nacional realizadas e agendadas na aplicação. | IT8 | Sim | Cenários, Léxicos, Backlog, História de Usuário | ELOB07, ELOF08 |
| RF09 | RF | O aplicativo deverá possuir uma tela intitulada “Fale Conosco” com informações de contato e perguntas frequentes dos usuários. | IT9 | Sim | Backlog, História de Usuário | ELOB08, ELOF09 |
| RF12 | RF | Permitir a visualização dos dados cadastrais do usuário (nome, cpf, email, celular). | IT12 | Sim | Léxicos, Backlog, História de Usuário | ELOB09, ELOF12 |
| RF13 | RF | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos. | IT13, GLO07 | Não | Léxicos, Backlog, História de Usuário | ELOB10, ELOF13 |
| RF14 | RF | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos. | IT14 | Não | Léxicos, Backlog, História de Usuário | ELOB11, ELOF14 |
| RF15 | RF | O sistema deve fornecer relatórios mensais contendo a evolução dos rendimentos dos títulos adquiridos pelo usuário com base nos meses anteriores. | IT15 | Não | Caso de Uso, Cenários, Léxicos, Backlog, História de Usuário | ELOB12, ELOF15 |
| RF16 | RF | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto. | IT16 e BF10 | Não | Backlog, História de Usuário | ELOB13, ELOF16 |
| RF17 | RF | Oferecer integração com carteiras digitais de outros bancos digitais para pagamento direto de investimentos. Atualmente as instituições financeiras integradas são “INTER DTVM LTDA”, “NU INVEST CORRETORA DE VALORES S.A” e “XP INVESTIMENTOS CCTVM S/A” | IT17 | Não | Backlog, História de Usuário | ELOB14, ELOF17 |
| RF18 | RF | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação. | IT18 | Não | Léxicos, Backlog, História de Usuário | ELOB15, ELOF18 |
| RF20 | RF | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente) durante o seu cadastro no sistema. | BF1 | Não | Backlog, História de Usuário | ELOB16, ELOF20 |
| RF21 | RF | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades. | BF2 | Não | Backlog, História de Usuário | ELOB17, ELOF21 |
| RF23 | RF | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação. | BF4 | Não | Cenários, Backlog, História de Usuário | ELOB18, ELOF23 |
| RF24 | RF | O sistema deverá disponibilizar uma ferramenta para simular a evolução do investimento em um título do tesouro nacional em comparação com outras opções de investimento como a poupança, LCI (Letra de Crédito Imobiliário) e LCA (Letra de Crédito do Agronegócio), Fundo de Renda Fixa Referenciado DI e CDB (Certificado de Depósito Bancário). | BF5, GF04 | Sim | Léxicos, Backlog, História de Usuário | ELOB19, ELOF24 |
| RF25 | RF | A tela de metas e sonhos deverá ser capaz de simular a evolução das metas | BF7 | Não | Caso de Uso, Cenários, Léxicos, Backlog, História de Usuário | ELOB20, ELOF25 |
| RF26 | RF | O aplicativo deve apresentar um dashboard com dados de rentabilidade dos títulos adquiridos e taxa de inflação. | BF8 | Não | Caso de Uso, Cenários, Backlog, História de Usuário | ELOB21, ELOF26 |
| RF27 | RF | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos". | BF12 | Não | Backlog, História de Usuário | ELOB22, ELOF27 |
| RF28 | RF | O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria. | BF14 | Não | Backlog, História de Usuário | ELOB23, ELOF28 |
| RF29 | RF | O sistema deve exibir sugestões personalizadas com base na expertise declarada pelo usuário na página inicial do "Meu Investimento". | BF15 | Não | Backlog, História de Usuário | ELOB24, ELOF29 |
| RF31 | RF | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento. | GLO02 | Sim | Backlog, História de Usuário | ELOB25, ELOF31 |
| RF32 | RF | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário. | GLO03 | Sim | Backlog, História de Usuário | ELOB26, ELOF32 |
| RF33 | RF | O aplicativo deverá permitir que o usuário faça cadastro na aplicação criando uma conta própria no sistema. | GF02 | Não | Caso de Uso, Backlog, História de Usuário | ELOB27, ELOF33 |
| RF34 | RF | O aplicativo deverá possuir a opção de realizar o login e cadastro a partir do sistema gov.br | GF01 | Sim | Caso de Uso, Léxicos, Backlog, História de Usuário | ELOB28, ELOF34 |
| RF35 | RF | Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois | IT20 | Sim | Caso de Uso, Backlog, História de Usuário | ELOB29, ELOF35 |
| RF36 | RF | O sistema deverá armazenar (preço unitário, rentabilidade, valor mínimo para investir, data de vencimento do título, pagamento de juros, taxa da BR, imposto de renda previsto sobre o rendimento, taxa de IOF) bem como informações a respeito do horário de funcionamento do mercado e tempo de liquidação dos juros. | IT1, GLO01 | Sim | Backlog, História de Usuário | ELOB30, ELOF36 |
| RF37 | RF | O sistema deverá possuir um simulador da evolução de um título do tesouro direto com base em um determinado período de tempo | IT7 | Sim | Backlog, História de Usuário | ELOB31, ELOF37 |
| RF38 | RF | O simulador deverá possuir um questionário para obter do usuário as informações necessárias para gerar o simulador. | IT7 | Sim | Léxicos, Backlog, História de Usuário | ELOB32, ELOF38 |
| RF39 | RF | O simulador deverá possuir as informações de: título do tesouro nacional que será usado, tempo de investimento e valor que será resgatado no futuro ou valor que será investido agora. | IT7 | Sim | Léxicos, Backlog, História de Usuário | ELOB33, ELOF39 |
| RF40 | RF | Cada meta deve possuir uma barra de progresso representando o progresso individual de conclusão da meta. | BF12 | Não | Backlog, História de Usuário | ELOB34, ELOF40 |
| RF41 | RF | As contas cadastradas na aplicação deverão possuir os dados de nome, cpf, email e celular do dono da conta. | GF02 | Sim | Backlog, História de Usuário | ELOB35, ELOF41 |
| RNF01 | RNF | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. | IT21 | Não | Especificação Suplementar, NFR Framework, Backlog, História de Usuário | ELOB36, ELONF01 |
| RNF02 | RNF | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD. | IT22, GF06 | Sim | Especificação Suplementar, Backlog, História de Usuário | ELOB37, ELONF02 |
| RNF03 | RNF | O aplicativo deve ser responsivo para dispositivos móveis e tablets. | IT23, GF07, GLO08 | Sim | Especificação Suplementar, NFR Framework, Backlog, História de Usuário | ELOB38, ELONF03 |
| RNF04 | RNF | A interface do aplicativo deve seguir as diretrizes de acessibilidade da norma técnica NBR 17060:2022 | IT24, BFN11, GF08, GLO04 | Não | Especificação Suplementar, NFR Framework, Backlog, História de Usuário | ELOB39, ELONF04 |
| RNF05 | RNF | O sistema deve permitir integrações seguras com APIs de instituições financeiras respeitando as normas da LGPD. | IT25, GLO06 | Sim | Especificação Suplementar, Backlog, História de Usuário | ELOB40, ELONF05 |
| RNF06 | RNF | O aplicativo deverá disponibilizar suporte para múltiplos idiomas (português como padrão). | IT26 | Não | Especificação Suplementar, Backlog, História de Usuário | ELOB41, ELONF06 |
| RNF08 | RNF | O perfil de recomendação de investimentos deve ser acessível a partir de 3 cliques de qualquer parte do aplicativo. | BFN9 | Não | Especificação Suplementar, NFR Framework, Backlog, História de Usuário | ELOB42, ELONF08 |
| RNF09 | RNF | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário. | BFN13 | Não | Especificação Suplementar, NFR Framework, Backlog, História de Usuário | ELOB43, ELONF09 |
| RNF10 | RNF | O sistema deverá garantir a segurança nas transações de títulos públicos. | GLO02 | Sim | Especificação Suplementar, Backlog, História de Usuário | ELOB44, ELONF10 |
| RNF11 | RNF | Os títulos do tesouro nacional deverão estar sempre atualizados com relação a inflação e a taxa de juros. | GLO03 | Sim | Especificação Suplementar, Backlog, História de Usuário | ELOB45, ELONF11 |

## Bibliografia

>  Requirements Engineering Fundamentals. Disponível em: [aqui](../assets/pos-rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 14 jan. 2025.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: [aqui](../assets/pos-rastreabilidade/requirements-fundamentals.pdf). Acesso em: 14 jan. 2025.

> Economia DF - "Rastreabilidade - Matriz de Rastreabilidade". Disponível em: [requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade](requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade). Acesso em: 14 jan. 2025.

## Histórico de Versões
|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|14/01/2025| Criação e ajuste do Documento |[Victor Rodrigues](https://github.com/ViictorHugoo) | |