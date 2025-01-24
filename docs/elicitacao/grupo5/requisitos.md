# Requisitos Elicitados

## Introdução 

Esta página reúne todos os requisitos elicitados pela equipe do projeto. As técnicas utilizadas foram [brainstorming](./brainstorm.md), [glossário](./glossario.md), [grupo de foco](./grupo-de-foco.md) e [introspecção](./introspeccao.md).

## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

_Legenda das Tabelas:_

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;
- ITx: Requisito da Introspecção número x;
- BFx: Requisito Funcional do Brainstorm número x;
- BFNx: Requisito Não Funcional do Brainstorm número x;
- GFx: Requisito do Grupo de Foco número x;
- GLOx: Requisito do Glossário número x;

### Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 1 - Requisitos Funcionais </a></font></p>
</div>

| Identificador | Descrição | ID | Implementado |
| :---- | :---- | :---- | :---- |
| <a id="anchor_RF01" style="visibility: hidden"></a>RF01 | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis com suas características principais: nome do título, rentabilidade, valor mínimo e vencimento. | [IT1](../introspeccao/#anchor_IT1), [GLO01](./glossario.md/#anchor_GLO01) | Sim |
| <a id="anchor_RF02" style="visibility: hidden"></a>RF02 | O sistema deverá permitir a simulação de investimento nos títulos SELIC, Prefixado e Inflação                                                                                          | [IT2](../introspeccao/#anchor_IT2) | Sim |
| <a id="anchor_RF03" style="visibility: hidden"></a>RF03 | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada.                              | [IT3](../introspeccao/#anchor_IT3), [GLO07](./glossario.md/#anchor_GLO07) | Sim | 
| <a id="anchor_RF04" style="visibility: hidden"></a>RF04 | Oferecer funcionalidade para salvar metas de investimentos (Sonhos). | [IT4](../introspeccao/#anchor_IT4) | Sim | 
| <a id="anchor_RF05" style="visibility: hidden"></a>RF05 | Permitir simulação e planejamento de aposentadoria indicando o ano esperado de aposentadoria. | [IT5](../introspeccao/#anchor_IT5) | Sim |  
| <a id="anchor_RF06" style="visibility: hidden"></a>RF06 | Disponibilizar consulta à taxa de custódia da B3 e taxa de administração da instituição financeira. | [IT6](../introspeccao/#anchor_IT6) | Sim | 
| <a id="anchor_RF08" style="visibility: hidden"></a>RF08 | Permitir a consulta de operações de compra de títulos do tesouro nacional realizadas e agendadas na aplicação. | [IT8](../introspeccao/#anchor_IT8) | Sim |
| <a id="anchor_RF09" style="visibility: hidden"></a>RF09 | O aplicativo deverá possuir uma tela intitulada “Fale Conosco” com informações de contato e perguntas frequentes dos usuários. | [IT9](../introspeccao/#anchor_IT9) | Sim |  
| <a id="anchor_RF12" style="visibility: hidden"></a>RF12 | Permitir a visualização dos dados cadastrais do usuário (nome, cpf, email, celular). | [IT12](../introspeccao/#anchor_IT12) | Sim |
| <a id="anchor_RF13" style="visibility: hidden"></a>RF13 | Implementar notificações personalizadas para lembrar o usuário de metas ou vencimento de títulos. | [IT13](../introspeccao/#anchor_IT13), [GLO07](./glossario.md/#anchor_GLO07) | Não |  
| <a id="anchor_RF14" style="visibility: hidden"></a>RF14 | Permitir a transferência automática entre investimentos com base em metas ou cenários predefinidos. | [IT14](../introspeccao/#anchor_IT14) | Não |  
| <a id="anchor_RF15" style="visibility: hidden"></a>RF15 | O sistema deve fornecer relatórios mensais contendo a evolução dos rendimentos dos títulos adquiridos pelo usuário com base nos meses anteriores. | [IT15](../introspeccao/#anchor_IT15) | Não | 
| <a id="anchor_RF16" style="visibility: hidden"></a>RF16 | Disponibilizar um recurso educativo com vídeos e artigos sobre como investir no Tesouro Direto. | [IT16](../introspeccao/#anchor_IT16) e [BF10](./brainstorm.md/#anchor_BF10) | Não |  
| <a id="anchor_RF17" style="visibility: hidden"></a>RF17| Oferecer integração com carteiras digitais de outros bancos digitais para pagamento direto de investimentos. Atualmente as instituições financeiras integradas são “INTER DTVM LTDA”, “NU INVEST CORRETORA DE VALORES S.A” e “XP INVESTIMENTOS CCTVM S/A” | [IT17](./introspeccao.md/#anchor_IT17) | Não |
| <a id="anchor_RF18" style="visibility: hidden"></a>RF18 | Incorporar alertas de mercado com base em mudanças na taxa SELIC ou inflação. | [IT18](./introspeccao.md/#anchor_IT18) | Não |
| <a id="anchor_RF20" style="visibility: hidden"></a>RF20 | O aplicativo deve permitir que o usuário faça uma autodeclaração de expertise (novo, médio, experiente) durante o seu cadastro no sistema. | [BF1](./brainstorm.md/#anchor_BF1) | Não |
| <a id="anchor_RF21" style="visibility: hidden"></a>RF21 | O aplicativo deve oferecer um tutorial para guiar o usuário no uso das funcionalidades. | [BF2](./brainstorm.md/#anchor_BF2) | Não |
| <a id="anchor_RF23" style="visibility: hidden"></a>RF23 | O aplicativo deve exibir a liquidez dos títulos do Tesouro Nacional na simulação. | [BF4](./brainstorm.md/#anchor_BF4) | Não | 
| <a id="anchor_RF24" style="visibility: hidden"></a>RF24 | O sistema deverá disponibilizar uma ferramenta para simular a evolução do investimento em um título do tesouro nacional em comparação com outras opções de investimento como a poupança, LCI (Letra de Crédito Imobiliário) e LCA (Letra de Crédito do Agronegócio), Fundo de Renda Fixa Referenciado DI e CDB (Certificado de Depósito Bancário). | [BF5](./brainstorm.md/#anchor_BF5), [GF04](./grupo-de-foco.md/#anchor_GF04) | Sim   |
| <a id="anchor_RF25" style="visibility: hidden"></a>RF25 | A tela de metas e sonhos deverá ser capaz de simular a evolução das metas | [BF7](./brainstorm.md/#anchor_BF7) | Não |
| <a id="anchor_RF26" style="visibility: hidden"></a>RF26 | O aplicativo deve apresentar um dashboard com dados de rentabilidade dos títulos adquiridos e taxa de inflação. | [BF8](./brainstorm.md/#anchor_BF8) | Não |
| <a id="anchor_RF27" style="visibility: hidden"></a>RF27 | O sistema deve incluir uma barra de progresso na aba "Meus Sonhos". | [BF12](./brainstorm.md/#anchor_BF12) | Não |
| <a id="anchor_RF28" style="visibility: hidden"></a>RF28 | O aplicativo deve permitir a comparação da simulação com os padrões do INSS na aposentadoria. | [BF14](./brainstorm.md/#anchor_BF14) | Não |  
| <a id="anchor_RF29" style="visibility: hidden"></a>RF29 | O sistema deve exibir sugestões personalizadas com base na expertise declarada pelo usuário na página inicial do "Meu Investimento". | [BF15](./brainstorm.md/#anchor_BF15) | Não | 
| <a id="anchor_RF31" style="visibility: hidden"></a>RF31 | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento. | [GLO02](./glossario.md/#anchor_GLO02) | Sim | 
| <a id="anchor_RF32" style="visibility: hidden"></a>RF32 | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário. | [GLO03](./glossario.md/#anchor_GLO03) | Sim | 
| <a id="anchor_RF33" style="visibility: hidden"></a>RF33 | O aplicativo deverá permitir que o usuário faça cadastro na aplicação criando uma conta própria no sistema. | [GF02](./grupo-de-foco.md/#anchor_GF02) | Não |
| <a id="anchor_RF34" style="visibility: hidden"></a>RF34 | O aplicativo deverá possuir a opção de realizar o login e cadastro a partir do sistema gov.br | [GF01](./grupo-de-foco.md/#anchor_GF01) | Sim |
| <a id="anchor_RF35" style="visibility: hidden"></a>RF35|Escolher meus investimentos, definir um valor para cada investimento e escolher entre investir agora ou investir depois|[IT20](./introspeccao.md/#anchor_IT20)|Sim|
| <a id="anchor_RF36" style="visibility: hidden"></a>RF36 | O sistema deverá armazenar (preço unitário, rentabilidade, valor mínimo para investir, data de vencimento do título, pagamento de juros, taxa da BR, imposto de renda previsto sobre o rendimento, taxa de IOF) bem como informações a respeito do horário de funcionamento do mercado e tempo de liquidação dos juros. | [IT1](./introspeccao.md/#anchor_IT1), [GLO01](./glossario.md/#anchor_GLO01) | Sim |
| <a id="anchor_RF37" style="visibility: hidden"></a>RF37 | O sistema deverá possuir um simulador da evolução de um título do tesouro direto com base em um determinado período de tempo | [IT7](./introspeccao.md/#anchor_IT7) | Sim |
| <a id="anchor_RF38" style="visibility: hidden"></a>RF38 | O simulador deverá possuir um questionário para obter do usuário as informações necessárias para gerar o simulador. | [IT7](./introspeccao.md/#anchor_IT7) | Sim |
| <a id="anchor_RF39" style="visibility: hidden"></a>RF39 | O simulador deverá possuir as informações de: título do tesouro nacional que será usado, tempo de investimento e valor que será resgatado no futuro ou valor que será investido agora. | [IT7](./introspeccao.md/#anchor_IT7) | Sim |
| <a id="anchor_RF40" style="visibility: hidden"></a>RF40 | Cada meta deve possuir uma barra de progresso representando o progresso individual de conclusão da meta. | [BF12](./brainstorm.md/#anchor_BF12) | Não |
| <a id="anchor_RF41" style="visibility: hidden"></a>RF41 | As contas cadastradas na aplicação deverão possuir os dados de nome, cpf, email e celular do dono da conta. | [GF02](./grupo-de-foco.md/#anchor_GF02) | Sim |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>


### Não Funcionais

<div>
<font size="3"><p style="text-align: center"> Tabela 2 - Requisitos Não Funcionais </a></font></p>
</div>

| Identificador | Descrição	| ID | Implementado |
|---------------|-----------|-----|-------------|
| <a id="anchor_RNF01" style="visibility: hidden"></a>RNF01 | O sistema deve ter tempo de resposta inferior a 2 segundos para consultas básicas. |  [IT21](../introspeccao/#anchor_IT21) | Não
| <a id="anchor_RNF02" style="visibility: hidden"></a>RNF02 | Garantir a segurança dos dados sensíveis do usuário conforme a LGPD. | [IT22](../introspeccao/#anchor_IT22), [GF06](./grupo-de-foco.md/#anchor_GF06) | Sim |
| <a id="anchor_RNF03" style="visibility: hidden"></a>RNF03 | O aplicativo deve ser responsivo para dispositivos móveis e tablets. | [IT23](../introspeccao/#anchor_IT23), [GF07](./grupo-de-foco.md/#anchor_GF07), [GLO08](./glossario.md/#anchor_GLO08) | Sim |
| <a id="anchor_RNF04" style="visibility: hidden"></a>RNF04 | A interface do aplicativo deve seguir as diretrizes de acessibilidade da norma técnica [NBR 17060:2022](HTTPS://WWW.ABNTCOLECAO.COM.BR/MPF/NORMA.ASPX?ID=516652#) | [IT24](../introspeccao/#anchor_IT24), [BFN11](./brainstorm.md/#anchor_BFN11), [GF08](./grupo-de-foco.md/#anchor_GF08), [GLO04](./glossario.md/#anchor_GLO04) | Não |
| <a id="anchor_RNF05" style="visibility: hidden"></a>RNF05 | O sistema deve permitir integrações seguras com APIs de instituições financeiras respeitando as normas da LGPD. | [IT25](../introspeccao/#anchor_IT25), [GLO06](./glossario.md/#anchor_GLO06) | Sim |
| <a id="anchor_RNF06" style="visibility: hidden"></a>RNF06 | O aplicativo deverá disponibilizar suporte para múltiplos idiomas (português como padrão). | [IT26](../introspeccao/#anchor_IT26) | Não |
| <a id="anchor_RNF08" style="visibility: hidden"></a>RNF08 | O perfil de recomendação de investimentos deve ser acessível a partir de 3 cliques de qualquer parte do aplicativo. | [BFN9](./brainstorm.md/#anchor_BFN9) | Não |
| <a id="anchor_RNF09" style="visibility: hidden"></a>RNF09 | O aplicativo deve incluir uma opção de tema escuro para melhorar a experiência do usuário. | [BFN13](./brainstorm.md/#anchor_BFN13) | Não |
| <a id="anchor_RNF10" style="visibility: hidden"></a>RNF10 | O sistema deverá garantir a segurança nas transações de títulos públicos. | [GLO02](./glossario.md/#anchor_GLO02) | Sim |
| <a id="anchor_RNF11" style="visibility: hidden"></a>RNF11 | Os títulos do tesouro nacional deverão estar sempre atualizados com relação a inflação e a taxa de juros. | [GLO03](./glossario.md/#anchor_GLO03) | Sim |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/ViictorHugoo">Victor Rodrigues, 2024</a></font></p>
</div>


## Requisitos por Integrante

<center>
<div id="anchor_req_integrante">
<font size="3"><p style="text-align: center">Tabela 3 - Requisitos por Integrante</p></font>
</div>

| Nome do Integrante                                  | Requisito Funcional                  | Requisito Não-Funcional            |
|----------------------------------------------------|--------------------------------------|------------------------------------|
| [Júlia Takaki](https://github.com/juliatakaki)     | [RF18](#anchor_RF18)                                   | [RNF06](#anchor_RNF06)                                 |
| [Maria Helena](https://github.com/MariaCHelena)    | [RF20](#anchor_RF20) e [RF29](#anchor_RF29) | -                                  |
| [Thales Euflauzino](https://github.com/thaleseuflauzino) | [RF15](#anchor_RF15)                               | [RNF08](#anchor_RNF08)                                  |
| [Víctor Schmidt](https://github.com/moonshinerd)   | [RF25](#anchor_RF25) e [RF33](#anchor_RF33)                 |             |
| [Víctor Rodrigues](https://github.com/ViictorHugoo)| [RF26](#anchor_RF26) e [RF40](#anchor_RF40) | -                                  |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://www.github.com/moonshinerd">Víctor Schmidt, 2024</a></p></font>
</div>
</center>

### Instruções do Professor

1. **Seleção dos Requisitos Funcionais:**  
    - Os requisitos funcionais escolhidos **devem obrigatoriamente não estar implementados** no aplicativo até o momento.

2. **Seleção dos Requisitos Não-Funcionais:**  
    - Os requisitos não-funcionais podem **estar ou não implementados** no aplicativo.

## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 21/11/2024 | Lista de requisitos | [Víctor Rodrigues](https://github.com/ViictorHugoo) | [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.1`  | 27/11/2024 | Adicionando anchor's para rastreabilidade |  [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.2`  | 11/12/2024 | Removendo, complementando e ajustando requisitos que foram mau ou pouco elaborados e adicionando tabela 3|  [Víctor Schmidt](https://github.com/moonshinerd) e [Maria Helena](https://github.com/MariaCHelena) | [Víctor Rodrigues](https://github.com/ViictorHugoo) e [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| `1.3`  | 11/12/2024 | Escolhendo requisitos para trabalho pessoal |  [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.4` | 12/12/2024  | Ajustes para pos-rastreabilidade | [Thales Euflauzino](https://github.com/thaleseuflauzino) |[Víctor Schmidt](https://github.com/moonshinerd)| 
| `1.5` | 23/01/2025  | Trocando tabela de requisitos trabalhados na diciplina de Victor Schmidt pois o RNF04 é inviável de implementar então o RF33 será feito no lugar dele | [Víctor Schmidt](https://github.com/moonshinerd) | [Thales Euflauzino](https://github.com/thaleseuflauzino) | 