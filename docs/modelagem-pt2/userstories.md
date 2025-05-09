# Histórias de Usuário

## Introdução

Histórias de usuários são usadas para capturar as necessidades e expectativas dos usuários finais de forma clara, simples e centrada no valor que será entregue. Elas são descrições breves que comunicam o que um usuário deseja alcançar ao interagir com o sistema.

## Metodologia

Para realizar a criação das histórias de usuário, foi utilizado o seguinte modelo estabelecido pelo SWEBOK <a href="REF1">[1]</a>:

"Como [tipo de usuário], eu quero [ação ou necessidade], para que [benefício ou propósito].".

Não somente isso, mas tendo como base o modelo de documentação de histórias de usuário definido pelo ministério da agricultura e pecuária <a href="REF2">[2]</a>, as histórias de usuário serão definidas com base no modelo descrito na tabela 1:

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Template Histórias de Usuário</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">USXX</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Exemplo de história 1</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td>Épico 1</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Critério 1</li>
                <li>Critério 2</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>USXX</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: [Maria Helena](https://github.com/MariaCHelena), 2024</p></font>

## Vídeo 1 - Entrevista com o Product Owner  

O vídeo 1, apresentado abaixo, contém a entrevista conduzida exclusivamente com o _Product Owner_ Adrian. Durante a gravação, Adrian respondeu a diversas perguntas formuladas por nossa equipe, contribuindo para a construção do backlog e para as histórias de usuário.  

O uso de sua imagem foi previamente autorizado, e sua declaração de consentimento pode ser vista no início do vídeo.  

<center>  

**Vídeo 1** - [Elaboração do Product Backlog com o PO](https://youtu.be/-Z8fSsVPz4U)  

<iframe width="560" height="315" src="https://www.youtube.com/embed/-Z8fSsVPz4U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

_Autor: [Víctor Schmidt](https://github.com/moonshinerd)_  

## Histórias de Usuário

As tabelas de usuário foram elaboradas seguindo o padrão presente na Tabela 1, e as Tabelas de 2 a 42 são as Histórias de Usuário de fato.

### <a id="anchor_US01" style="visibility: hidden"></a>US01 - Visualizar a lista de títulos públicos disponíveis

<details>
<summary>Tabela 2 - US01 - Visualizar a lista de títulos públicos disponíveis</summary>
<font size="2"><p style="text-align: center"><bol>Tabela 2</bol> - História de Usuário Visualizar a lista de títulos públicos disponíveis</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US01 - Visualizar a lista de títulos públicos disponíveis</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo visualizar a lista de títulos públicos disponíveis e suas características principais como nome, título, rentabilidade, valor mínimo e vencimento para conhecer mais sobre os títulos e realizar investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec01-visualizacao-de-titulos-publicos">EC01</a> - Visualização de Títulos Públicos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> Os Títulos deverão ser exibidos de ordem do mais recente para o mais antigo </li>
              <li> Os títulos devem ser agrupados de acordo com o seu tipo, ou seja, agrupados por títulos vinculados a Selic, vinculados à inflação e pré-fixados. </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US01</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US02" style="visibility: hidden"></a>US02 - 	Simulação de investimento nos títulos

<details>
<summary>Tabela 3 - US02 - 	Simulação de investimento nos títulos SELIC, Prefixado e Inflação.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - História de Usuário Simulação de investimento nos títulos SELIC, Prefixado e Inflação.</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US02 - 	Simulação de investimento nos títulos SELIC, Prefixado e Inflação</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo realizar a simulação da evolução do meu título para planejar os meus investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> A simulação deverá estar disponível para todos os títulos listados no aplicativo </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US02</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US03" style="visibility: hidden"></a>US03 - Resgate antecipado de títulos

<details>
<summary>Tabela 4 - US03 - Resgate antecipado de títulos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 3</b> - História de Usuário Resgate antecipado de títulos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US03 - Resgate antecipado de títulos</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo realizar o resgate antecipado dos títulos, para obter imediatamente o valor investido nesse título.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> O cálculo do valor líquido que será obtido no resgate deverá ser realizado automaticamente com base na data de resgate e rentabilidade acumulada </li>
              <li> O resgate antecipado deve estar disponível em todos os títulos do aplicativo </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US03</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US04" style="visibility: hidden"></a>US04 - Salvar metas de investimentos (Sonhos).

<details>
<summary>Tabela 5 - US04 - Salvar metas de investimentos (Sonhos)</summary>
<font size="2"><p style="text-align: center"><b>Tabela 5</b> - História de Usuário Salvar metas de investimentos (Sonhos)</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US04 - Salvar metas de investimentos (Sonhos)</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo salvar as minhas metas de investimento no aplicativo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09</a> - Personalização de Metas e Planejamento Financeiro</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> O usuário deve poder criar quantas metas quiser </li>
              <li> O usuário deve ser capaz de customizar as metas definindo um nome para a meta e quantidade de dinheiro que deseja investir </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US04</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US05" style="visibility: hidden"></a>US05 - Simulação e planejamento de aposentadoria

<details>
<summary>Tabela 6 - US05 - Simulação e planejamento de aposentadoria</summary>
<font size="2"><p style="text-align: center"><b>Tabela 6</b> - História de Usuário Simulação e planejamento de aposentadoria</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US05 - Simulação e planejamento de aposentadoria</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo realizar a simulação e o planejamento financeiro da minha aposentadoria para obter esses dados com base nos títulos do tesouro nacional</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec10-simuladores-avancados">EC10</a> - Simuladores Avançados </td></td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> Para realizar a simulação o usuário deve indicar o ano esperado de aposentadoria </li>
              <li> A simulação de aposentadoria deve estar disponível para todos os títulos públicos </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US05</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US06" style="visibility: hidden"></a>US06 - Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira.

<details>
<summary>Tabela 7 - US06 - Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 7</b> História de Usuário Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US06 - Consulta à taxa de custódia da B3 e taxa de administração da instituição financeira</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo realizar a consulta à taxa de custódia da B3 e a taxa de administração da instituição financeira na qual o título será adquirido, para entender os custos relacionados ao meu investimento de interesse</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec04-painel-de-controle-e-relatorios">EC04</a> - Painel de Controle e Relatórios</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> Deve estar disponível as taxas administrativas de todas as instituições vinculadas ao aplicativo do tesouro direto. </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US06</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US07" style="visibility: hidden"></a>US07 - Consulta de operações de compra realizadas e agendadas

<details>
<summary>Tabela 8 - US07 - Consulta de operações de compra realizadas e agendadas</summary>
<font size="2"><p style="text-align: center"><b>Tabela 8</b> - História de Usuário Consulta de operações de compra realizadas e agendadas</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US07 - Consulta de operações de compra realizadas e agendadas</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo realizar a consulta de compras realizadas e agendadas na aplicação para me atualizar da situação dos meus investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos - Processo de Compra de Títulos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
            <ol>
              <li> Todos os títulos que foram adiquiridos através do aplicativo deverão exibir o seu status de compra </li>
            </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US07</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US08" style="visibility: hidden"></a>US08 - Fale Conosco

<details>
<summary>Tabela 9 - US08 - Fale Conosco</summary>
<font size="2"><p style="text-align: center"><b>Tabela 9</b> - História de Usuário Fale Conosco</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US08 - Fale Conosco</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo ter acesso a informações de contato com a equipe do tesouro direto e perguntas frequentes realizadas pelos usuários, para obter ajuda com as minhas dúvidas referentes às funcionalidades do aplicativo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec12-integracao-com-canais-de-atendimento">EC12</a> - Integração com Canais de Atendimento</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>As informações de contato e perguntas frequentes deverão estar disponíveis em uma tela chamada "Fale Conosco"</li>
                <li>A tela "Fale Conosco" deverá possuir pelo menos 5 perguntas frequentes</li>
                <li>A tela "Fale Conosco" deverá possuir pelo menos um número de contato e um email</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US08</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US09" style="visibility: hidden"></a>US09 - Visualização dos dados cadastrais do usuário

<details>
<summary>Tabela 10 - US09 - Visualização dos dados cadastrais do usuário</summary>
<font size="2"><p style="text-align: center"><b>Tabela 10</b> - História de Usuário Visualização dos dados cadastrais do usuário</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US09 - Visualização dos dados cadastrais do usuário</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo visualizar minhas informações cadastradas na aplicação para obter informação a respeito dos meus dados na aplicação</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec11-gerenciamento-de-dados-do-usuario">EC11</a> - Gerencimaneot de Dados do Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Deve ser possível visualizar os dados de nome, email, cpf e telefone do usuário</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US09</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US10" style="visibility: hidden"></a>US10 - Notificações de lembrete de metas ou vencimento de títulos

<details>
<summary>Tabela 11 - US10 - Notificações de lembrete de metas ou vencimento de títulos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 11</b> - História de Usuário Notificações de lembrete de metas ou vencimento de títulos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US10 - Notificações de lembrete de metas ou vencimento de títulos</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo visualizar notificações personalizadas de vencimento de títulos e metas para obter os status atualizados dos meus investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos e <a href="../backlog/#ec12-integracao-com-canais-de-atendimento">EC12</a> - Integração com Canais de Atendimento</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O usuário deve receber notificações sempre que faltar 1 dia, 1 semana e 1 mês para o vencimento dos títulos e metas</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US10</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US11" style="visibility: hidden"></a>US11 - Transferência automática entre investimentos

<details>
<summary>Tabela 12 - US11 - Transferência automática entre investimentos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 12</b> - Histórias de Usuário Transferência automática entre investimentos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US11 - Transferência automática entre investimentos</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo que seja feita uma transferência automática entre investimentos com base em minhas metas, para que o meu dinheiro continue investido quando o prazo do investimento for finalizado</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec02-gerenciamento-de-investimentos">EC02</a>- Gerenciamento de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Todas as metas deverão fazer a transferência automática assim que o investimento aplicado tenha vencido</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US11</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US12" style="visibility: hidden"></a>US12 - Relatórios mensais de investimento

<details>
<summary>Tabela 13 - US12 - Relatórios mensais de investimento</summary>
<font size="2"><p style="text-align: center"><b>Tabela 13</b> - Histórias de Usuário Relatórios mensais de investimento</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US12 - Relatórios mensais de investimento</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo receber relatórios mensais dos meus investimentos, para poder visualizar dados de evolução dos investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec04-painel-de-controle-e-relatorios">EC04</a> - Painel de Controle e Relatórios</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Os usuários devem receber relatórios todos os meses</li>
                <li>Todos os investimentos ativos realizados pelo usuário devem estar presentes no relatório</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US12</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino">Thales Euflauzino</a>, 2024</p></font>
</details>

### <a id="anchor_US13" style="visibility: hidden"></a>US13 - Recursos educativos sobre como investir no Tesouro Direto

<details>
<summary>Tabela 14 - US13 - Recursos educativos sobre como investir no Tesouro Direto</summary>
<font size="2"><p style="text-align: center"><b>Tabela 14</b> - História de Usuário Recursos educativos sobre como investir no Tesouro Direto</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US13 - Recursos educativos sobre como investir no Tesouro Direto</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo visualizar recursos educativos para aprender mais sobre como investir no Tesouro Direto</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec08-recursos-educativos">EC08</a> - Recursos Educativos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Os recursos educativos devem conter textos, fotos e vídeos</li>
                <li>Os recursos educativos devem conter um glossário para mais termos utilizados no app do tesouro direto</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US13</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US14" style="visibility: hidden"></a>US14 - Integração com carteiras digitais

<details>
<summary>Tabela 15 - US14 - Integração com carteiras digitais</summary>
<font size="2"><p style="text-align: center"><b>Tabela 15</b> - Histórias de Usuário Integração com carteiras digitais</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US14 - Integração com carteiras digitais</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, como usuário, desejo que o aplicativo possua integração com carteiras digitais para que eu possa realizar a compra dos títulos do tesouro direto</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec02-gerenciamento-de-investimentos">EC02</a> - Gerenciamento de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O aplicativo deve possuir integração com as seguintes instituições financeiras:
                    <ul>
                        <li>INTER DTVM LTDA</li>
                        <li>NU INVEST CORRETORA DE VALORES S.A</li>
                        <li>XP INVESTIMENTOS CCTVM S/A</li>
                    </ul>
                </li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US14</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino"> Thales Euflauzino </a>, 2024</p></font>
</details>

### <a id="anchor_US15" style="visibility: hidden"></a>US15 - Alertas de mercado

<details>
<summary>Tabela 16 - US15 - Alertas de mercado</summary>
<font size="2"><p style="text-align: center"><b>Tabela 16</b> - História de Usuário Alertas de mercado</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US15</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero receber alertas personalizados sobre mudanças na taxa SELIC e inflação, para que eu possa ajustar meus investimentos com base no mercado.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec15-atualizacoes-e-notificacoes-automaticas">EC15</a> - Atualizações e Notificações Automáticas</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema envia notificações automáticas quando há alterações relevantes nas taxas.</li>
                <li>O usuário pode configurar os limites ou condições para receber os alertas.</li>
                <li>As notificações incluem informações resumidas e um link para detalhes.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US15</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/juliatakaki"> Júlia Takaki </a>, 2024</p></font>
</details>

### <a id="anchor_US16" style="visibility: hidden"></a>US16 - Autodeclaração de expertise

<details>
<summary>Tabela 17 - US16 - Autodeclaração de expertise</summary>
<font size="2"><p style="text-align: center"><b>Tabela 17</b> - História de Usuário Autodeclaração de expertise</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US16</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um novo usuário, eu quero declarar minha expertise no momento do cadastro, para que o sistema personalize minhas sugestões e recursos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec05-cadastro-e-personalizacao-de-usuario">EC05</a> - Cadastro e Personalização de Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O cadastro inclui uma etapa para declaração de expertise (iniciante, médio ou experiente).</li>
                <li>As sugestões apresentadas no sistema refletem o nível de expertise selecionado.</li>
                <li>O nível de expertise pode ser alterado posteriormente nas configurações do usuário.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US16</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US17" style="visibility: hidden"></a>US17 - Tutorial no uso das funcionalidades

<details>
<summary>Tabela 18 - US17 - Tutorial no uso das funcionalidades</summary>
<font size="2"><p style="text-align: center"><b>Tabela 18</b> - História de Usuário Tutorial no uso das funcionalidades</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US17</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um novo usuário, eu quero acessar um tutorial sobre as funcionalidades do aplicativo, para que eu possa utilizá-lo de forma eficiente desde o início.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec08-recursos-educativos">EC08</a> - Recursos Educativos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O tutorial é exibido automaticamente na primeira vez que o aplicativo é aberto.</li>
                <li>O usuário pode revisitar o tutorial a qualquer momento nas configurações.</li>
                <li>O tutorial cobre as principais funcionalidades, como investimentos, relatórios e simulações.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US17</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino"> Thales Euflauzino </a>, 2024</p></font>
</details>

### <a id="anchor_US18" style="visibility: hidden"></a>US18 - Liquidez dos títulos na simulação.

<details>
<summary>Tabela 19 - US18 - Liquidez dos títulos na simulação.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 19</b> - História de Usuário Liquidez dos títulos na simulação.</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US18</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um investidor, eu quero visualizar a liquidez dos títulos simulados, para que eu possa avaliar a melhor opção para meu perfil de investimento.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O simulador exibe a liquidez de cada título no resultado da simulação.</li>
                <li>A liquidez é calculada com base nos dados atualizados do Tesouro Nacional.</li>
                <li>As informações de liquidez são destacadas na interface.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US18</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino"> Thales Euflauzino </a>, 2024</p></font>
</details>

### <a id="anchor_US19" style="visibility: hidden"></a>US19 - Comparação de Investimentos

<details>
<summary>Tabela 20 - US19 - Comparação de Investimentos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 20</b> - História de Usuário Comparação de Investimentos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US19</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero simular a evolução dos títulos do Tesouro Direto em comparação com outras opções, para que eu possa tomar decisões informadas sobre meus investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema deve incluir comparações com opções como poupança, LCI, LCA, Fundo DI e CDB.</li>
                <li>O simulador exibe gráficos e tabelas comparativas.</li>
                <li>As taxas e rendimentos das opções são atualizados automaticamente no sistema.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US19</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino"> Thales Euflauzino </a>, 2024</p></font>
</details>

### <a id="anchor_US20" style="visibility: hidden"></a>US20 - Simular a evolução das metas

<details>
<summary>Tabela 21 - US20 - Simular a evolução das metas</summary>
<font size="2"><p style="text-align: center"><b>Tabela 21</b> - História de Usuário Simular a evolução das metas</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US20</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero simular a evolução das minhas metas na tela de "Meus Sonhos", para que eu possa ajustar meu planejamento conforme necessário.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09</a> - Personalização de Metas e Planejamento Financeiro</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema permite visualizar o progresso de cada meta em relação ao valor-alvo.</li>
                <li>O usuário pode realizar simulações ajustando prazos ou valores investidos.</li>
                <li>As simulações são exibidas de forma gráfica e interativa.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US20</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US21" style="visibility: hidden"></a>US21 - Dashboard com dados de rentabilidade e inflação.

<details>
<summary>Tabela 22 - US21 - Dashboard com dados de rentabilidade e inflação.</summary>
<font size="2"><p style="text-align: center"><b>Tabela 22</b> - História de Usuário Dashboard com dados de rentabilidade e inflação.</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US21</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero acessar um dashboard que exiba a rentabilidade dos meus títulos e a taxa de inflação, para que eu possa ter uma visão geral dos meus investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec04-painel-de-controle-e-relatorios">EC04</a> - Painel de Controle e Relatórios</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O dashboard apresenta gráficos interativos de rentabilidade e inflação.</li>
                <li>O usuário pode personalizar os dados exibidos no painel.</li>
                <li>O sistema atualiza os dados em tempo real.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US21</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US22" style="visibility: hidden"></a>US22 - Barra de progresso em "Meus Sonhos".

<details>
<summary>Tabela 23 - US22 - Barra de progresso em "Meus Sonhos".</summary>
<font size="2"><p style="text-align: center"><b>Tabela 23</b> - História de Usuário Barra de progresso em "Meus Sonhos"</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US22</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero visualizar uma barra de progresso em cada meta na aba "Meus Sonhos", para que eu saiba quanto falta para atingir meu objetivo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09</a> - Personalização de Metas e Planejamento Financeiro</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>A barra de progresso é atualizada automaticamente com base nos valores investidos.</li>
                <li>O progresso é exibido em porcentagem e valores absolutos.</li>
                <li>O design da barra é visível em diferentes dispositivos.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US22</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino"> Thales Euflauzino </a>, 2024</p></font>
</details>

### <a id="anchor_US23" style="visibility: hidden"></a>US23 - Comparação da simulação com os padrões do INSS.

<details>
<summary>Tabela 24 - US23 - Comparação da simulação com os padrões do INSS</summary>
<font size="2"><p style="text-align: center"><b>Tabela 24</b> - História de Usuário Comparação da simulação com os padrões do INSS.</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US23</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero comparar minha simulação de aposentadoria com os padrões do INSS, para que eu entenda as vantagens de investir no Tesouro Direto.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec10-simuladores-avancados">EC10</a> - Simuladores Avançados</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>A comparação exibe os valores estimados de aposentadoria com INSS e com investimentos no Tesouro Direto.</li>
                <li>O sistema permite ajustar os parâmetros do INSS, como tempo de contribuição.</li>
                <li>O comparativo é exibido de forma gráfica e textual.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US23</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US24" style="visibility: hidden"></a>US24 - Sugestões com base na expertise

<details>
<summary>Tabela 25 - US24 - Sugestões com base na expertise</summary>
<font size="2"><p style="text-align: center"><b>Tabela 25</b> - História de Usuário Sugestões com base na expertise</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US24</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero visualizar sugestões personalizadas com base na minha expertise, para que eu possa acessar conteúdos relevantes e de acordo com meu perfil.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec05-cadastro-e-personalizacao-de-usuario">EC05</a> - Cadastro e Personalização de Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>As sugestões são exibidas na página inicial "Meu Investimento".</li>
                <li>O conteúdo sugerido é baseado no nível de expertise declarado pelo usuário.</li>
                <li>As sugestões podem incluir artigos, vídeos ou investimentos recomendados.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US24</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US25" style="visibility: hidden"></a>US25 - Métodos de pagamento para compra de títulos

<details>
<summary>Tabela 26 - US25 - Métodos de pagamento para compra de títulos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 26</b> - História de Usuário Métodos de pagamento para compra de títulos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US25</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero comprar títulos públicos com diferentes métodos de pagamento, para que eu tenha flexibilidade nas transações.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec07-processo-de-compra-de-titulos">EC07</a> - Processo de Compra de Títulos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema aceita pagamento via transferência bancária, PIX e débito automático.</li>
                <li>As opções de pagamento são exibidas no momento da compra.</li>
                <li>A transação é confirmada com um comprovante enviado ao usuário.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US25</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US26" style="visibility: hidden"></a>US26 - Rentabilidade acumulada de títulos

<details>
<summary>Tabela 27 - US26 - Rentabilidade acumulada de títulos</summary>
<font size="2"><p style="text-align: center"><b>Tabela 27</b> - História de Usuário Rentabilidade acumulada de títulos</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US26</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero visualizar a rentabilidade acumulada de cada título na minha carteira, para que eu possa monitorar meu portfólio de investimentos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec04-painel-de-controle-e-relatorios">EC04</a> - Painel de Controle e Relatórios</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema apresenta a rentabilidade acumulada em um painel de controle.</li>
                <li>O usuário pode filtrar os dados por período ou tipo de título.</li>
                <li>Os valores exibidos são atualizados em tempo real.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US26</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US27" style="visibility: hidden"></a>US27 - Cadastro no próprio sistema

<details>
<summary>Tabela 28 - US27 - Cadastro no próprio sistema</summary>
<font size="2"><p style="text-align: center"><b>Tabela 28</b> - História de Usuário Cadastro no próprio sistema</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US27</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero criar uma conta no sistema, para que eu possa acessar todas as funcionalidades do aplicativo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec05-cadastro-e-personalizacao-de-usuario">EC05</a> - Cadastro e Personalização de Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema oferece campos para nome, CPF, e-mail e celular.</li>
                <li>O usuário recebe um e-mail de confirmação após o cadastro.</li>
                <li>As informações fornecidas são validadas automaticamente pelo sistema.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US27</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US28" style="visibility: hidden"></a>US28 - Login e cadastro a partir do sistema gov.br

<details>
<summary>Tabela 29 - US28 - Login e cadastro a partir do sistema gov.br</summary>
<font size="2"><p style="text-align: center"><b>Tabela 29</b> - História de Usuário Login e cadastro a partir do sistema gov.br</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US28</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero realizar meu cadastro e login pelo sistema gov.br, para que eu possa acessar o aplicativo de forma prática e segura.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec05-cadastro-e-personalizacao-de-usuario">EC05</a> - Cadastro e Personalização de Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema oferece a opção de integração com o gov.br.</li>
                <li>O login e o cadastro via gov.br são seguros e compatíveis com a LGPD.</li>
                <li>O sistema sincroniza os dados automaticamente após o login.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US28</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US29" style="visibility: hidden"></a>US29 - Agendamento de Compras

<details>
<summary>Tabela 30 - US29 - Agendamento de Compras</summary>
<font size="2"><p style="text-align: center"><b>Tabela 30</b> - História de Usuário Agendamento de Compras</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US29</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero escolher meus investimentos, definir um valor e optar por investir agora ou depois, para que eu possa gerenciar melhor meus recursos financeiros.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec02-gerenciamento-de-investimentos">EC02</a> - Gerenciamento de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O usuário pode selecionar o título desejado.</li>
                <li>O sistema oferece opção de investimento imediato ou agendado.</li>
                <li>O agendamento é confirmado por notificações.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US29</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd"> Victor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US30" style="visibility: hidden"></a>US30 - Armazenamento de Informações dos Títulos e do Mercado

<details>
<summary>Tabela 31 - US30 - Armazenamento de Informações dos Títulos e do Mercado</summary>
<font size="2"><p style="text-align: center"><b>Tabela 31</b> - História de Usuário Armazenamento de Informações dos Títulos e do Mercado</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US30</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um usuário, eu quero que o sistema armazene e exiba as principais informações sobre os títulos públicos e o mercado, para que eu possa consultar esses dados facilmente e tomar decisões informadas.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec01-visualizacao-de-titulos-publicos">EC01</a> - Visualização de Títulos Públicos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema armazena e apresenta os seguintes dados dos títulos públicos: Preço unitário; Rentabilidade; Valor mínimo para investir; Data de vencimento; Pagamento de juros; Taxa da B3; Imposto de renda previsto sobre o rendimento; Taxa de IOF.</li>
                <li>O sistema exibe informações sobre o horário de funcionamento do mercado financeiro e o tempo de liquidação dos juros.</li>
                <li>Os dados armazenados são atualizados automaticamente em tempo real com base nas variações do mercado.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US30</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US31" style="visibility: hidden"></a>US31 - Simular evolução de um título com base em período de tempo

<details>
<summary>Tabela 32 - US31 - Simular evolução de um título com base em período de tempo</summary>
<font size="2"><p style="text-align: center"><b>Tabela 32</b> - História de Usuário Simular evolução de um título com base em período de tempo</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US32</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero simular a evolução de um título com base em um período de tempo, para que eu possa prever a rentabilidade do investimento.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O simulador permite configurar o período desejado.</li>
                <li>O sistema calcula a evolução com base nas taxas e características do título.</li>
                <li>O resultado da simulação é apresentado em gráficos de fácil visualização.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US31</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US32" style="visibility: hidden"></a> US32 - Questionário de informações necessárias para gerar o simulador.

<details>
<summary>Tabela 33 - US32 - Questionário de informações necessárias para gerar o simulador</summary>
<font size="2"><p style="text-align: center"><b>Tabela 33</b> - História de Usuário Questionário de informações necessárias para gerar o simulador</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US33</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um investidor, eu quero responder a um questionário no simulador, para que as simulações geradas estejam alinhadas ao meu perfil e objetivos.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O questionário coleta dados como perfil de risco, prazo de investimento e objetivo financeiro.</li>
                <li>O simulador ajusta os resultados com base nas respostas do usuário.</li>
                <li>O questionário pode ser revisado e ajustado pelo investidor.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US32</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US33" style="visibility: hidden"></a>US33 - Simulação de Metas

<details>
<summary>Tabela 34 - US33 - Simulação de Metas</summary>
<font size="2"><p style="text-align: center"><b>Tabela 34</b> - História de Usuário Simulação de Metas</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US33</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como investidor, eu quero usar um simulador que inclua tempo de investimento, valor investido, e valor de resgate, para que eu possa planejar minhas metas financeiras.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec03-simulacoes-de-investimentos">EC03</a> - Simulações de Investimentos</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O simulador solicita informações como título, valor investido e tempo de investimento.</li>
                <li>O sistema calcula e apresenta o valor estimado de resgate futuro.</li>
                <li>As informações são exibidas em gráficos e tabelas para melhor compreensão.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US33</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US34" style="visibility: hidden"></a>US34 - Meta com barra de progresso individual

<details>
<summary>Tabela 35 - US34 - Meta com barra de progresso individual</summary>
<font size="2"><p style="text-align: center"><b>Tabela 35</b> - História de Usuário Meta com barra de progresso individual</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US34</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como usuário, eu quero visualizar uma barra de progresso individual para cada meta, para que eu tenha clareza sobre o status de cada objetivo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec09-personalizacao-de-metas-e-planejamento-financeiro">EC09</a> - Personalização de Metas e Planejamento Financeiro</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Cada meta possui sua barra de progresso específica.</li>
                <li>A barra é destacada ao selecionar uma meta específica.</li>
                <li>O sistema permite alternar entre metas facilmente.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US34</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/ViictorHugoo"> Victor Rodrigues </a>, 2024</p></font>
</details>

### <a id="anchor_US35" style="visibility: hidden"></a>US35 - Validação de usuário

<details>
<summary>Tabela 36 - US35 - Validação de usuário</summary>
<font size="2"><p style="text-align: center"><b>Tabela 36</b> - História de Usuário Validação de usuário</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US35</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Como um usuário, eu quero que meu cadastro inclua validação de dados pessoais, para que eu evite erros no preenchimento.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec11-gerenciamento-de-dados-do-usuario">EC11</a> - Gerenciamento de Dados do Usuário</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O sistema valida CPF, e-mail e número de celular no momento do cadastro.</li>
                <li>Campos obrigatórios são destacados e o usuário recebe feedback em caso de erro.</li>
                <li>O sistema exibe mensagens de sucesso ao concluir o cadastro corretamente.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US35</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/thaleseuflauzino">Thales Euflauzino </a> e <a href="https://github.com/moonshinerd">Víctor Schmidt </a>, 2024</p></font>
</details>

### <a id="anchor_US36" style="visibility: hidden"></a>US36 - Tema Escuro

<details>
<summary>Tabela 37 - US36 - Tema Escuro</summary>
<font size="2"><p style="text-align: center"><b>Tabela 37</b> - História de Usuário Tema Escuro</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US36</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, quero que poder escolher entre tema claro e escuro, para melhorar a minha experiência no aplicativo.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec13-funcionalidades-de-acessibilidade">EC13</a> - Funcionalidades de Acessibilidade</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>Todo o aplicativo deverá possuir uma versão no tema escuro.</li>
                <li>A versão padrão do aplicativo deve ser de tema claro.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US36</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US37" style="visibility: hidden"></a>US37 - Ajuste da Velocidade do Áudio

<details>
<summary>Tabela 38 - US37 - Ajuste da Velocidade do Áudio</summary>
<font size="2"><p style="text-align: center"><b>Tabela 38</b> - História de Usuário Ajuste da Velocidade do Áudio</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US37</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, desejo ajustar a velocidade dos áudios disponíveis no aplicativo para melhorar minha compreensão dos conteúdos de áudio.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec13-funcionalidades-de-acessibilidade">EC13</a> - Funcionalidades de Acessibilidade</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O áudio deverá estar na velocidade normal por padrão.</li>
                <li>O áudio deverá possuir as seguintes opções de velocidade:
                    <ul>
                        <li>0.25x</li>
                        <li>0.5x</li>
                        <li>0.75x</li>
                        <li>1x</li>
                        <li>1.25x</li>
                        <li>1.5x</li>
                        <li>1.75x</li>
                        <li>2x</li>
                    </ul>
                </li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US37</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a>, 2024</p></font>
</details>

### <a id="anchor_US38" style="visibility: hidden"></a>US38 - Mudança de idioma do aplicativo

<details>
<summary>Tabela 39 - US38 - Mudança de idioma do aplicativo</summary>
<font size="2"><p style="text-align: center"><b>Tabela 39</b> - História de Usuário Mudança de idioma do aplicativo</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US38</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, desejo poder alterar o idioma do aplicativo para acessar o aplicativo no idioma mais adequado para mim.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec14-multilingue-e-inclusao">EC14</a> - Multilingue e inclusão</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O idioma padrão deverá ser o português brasileiro.</li>
                <li>Além do portugês brasileiro, o aplicativo deverá possuir as seguintes opções de idiomas:
                    <ol>
                        <li>Inglês</li>
                        <li>Espanhol</li>
                    </ol>
                </li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US38</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/juliatakaki">Júlia Takaki</a>, 2024</p></font>
</details>

### <a id="anchor_US39" style="visibility: hidden"></a>US39 - Segurança dos Dados

<details>
<summary>Tabela 40 - US39 - Segurança dos Dados</summary>
<font size="2"><p style="text-align: center"><b>Tabela 40</b> - História de Usuário Segurança dos Dados</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US39</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, desejo ter segurança na navegação no aplicativo, para garantir a segurança dos meus dados.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec06-seguranca-e-acessibilidade">EC06</a> - Segurança e Acessibilidade</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>O aplicativo deve seguir os critérios de segurança da LGPD.</li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Alta</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US39</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US40" style="visibility: hidden"></a>US40 - Responsividade do aplicativo

<details>
<summary>Tabela 41 - US40 - Responsividade do aplicativo</summary>
<font size="2"><p style="text-align: center"><b>Tabela 41</b> - História de Usuário Responsividade do aplicativo</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US40</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, desejo poder acessar o dispositivo em qualquer tablet ou celular compatível .</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec06-seguranca-e-acessibilidade">EC06</a> - Segurança e Acessibilidade</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>A interface do aplicativo deve se ajustar automaticamente a diferentes tamanhos de tela, incluindo smartphones e tablets.</li>
                <li>Todos os elementos da interface (botões, textos, imagens e formulários) devem ser visíveis e funcionais sem necessidade de zoom ou rolagem para baixo para mais de metade da tela</li>
                </li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Média</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US40</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/MariaCHelena">Maria Helena</a>, 2024</p></font>
</details>

### <a id="anchor_US41" style="visibility: hidden"></a>US41 - Acessibilidade Visual

<details>
<summary>Tabela 42 - US41 - Mudança de idioma do aplicativo</summary>
<font size="2"><p style="text-align: center"><b>Tabela 42</b> - História de Usuário Acessibilidade Visual</p></font>
<div style="display: flex; justify-content: center">
<table border="1">
  <thead>
      <tr>
          <th colspan="2" style="text-align: center;">US41</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td style="font-weight: bold;">História de Usuário</td>
          <td>Eu, Como um usuário, desejo navegar em um aplicativo acessível para que eu consiga utilizar todas as funcionalidades do aplicativo com facilidade.</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Épico</td>
          <td><a href="../backlog/#ec06-seguranca-e-acessibilidade">EC06</a> - Segurança e Acessibilidade</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Critérios de Aceitação</td>
          <td>
              <ol>
                <li>A interface deve seguir as diretrizes da norma <a href="https://www.abntcolecao.com.br/mpf/norma.aspx?ID=516652#">NBR 17060:2022</a> para acessibilidade visual, garantindo:
                    <ol>
                        <li>Contraste adequado entre texto e fundo, conforme padrões mínimos de luminância.</li>
                        <li>Tamanho de fonte ajustável, permitindo ampliação sem distorção do layout.</li>
                        <li>Uso de texto alternativo (alt text) para imagens e ícones informativos.</li>
                        <li>Foco visível e navegabilidade através de teclado e leitores de tela.</li>
                    </ol>
                </li>
              </ol>
          </td>
      </tr>
      <tr>
          <td style="font-weight: bold;">Prioridade</td>
          <td>Baixa</td>
      </tr>
      <tr>
          <td style="font-weight: bold;">ID</td>
          <td>US41</td>
      </tr>
  </tbody>
</table>
</div>
<font size="2"><p style="text-align: center">Autor: <a href="https://github.com/moonshinerd">Víctor Schmidt</a>, 2024</p></font>
</details>

## Validação 

No vídeo 2 apresenta-se a gravação da validação das User Stories.

<center>  

**Vídeo 2** - [Validação das User Stories](https://youtu.be/fwo7u_YgzEU)  

<iframe width="560" height="315" src="https://www.youtube.com/embed/fwo7u_YgzEU?si=CcT29-hv9IfTl_Dl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

_Autor: [Victor Rodrigues](https://github.com/ViictorHugoo)_  

</center>



## Referência Bibliográfica
> <span id="REF1">1.</span> Washizaki, Hironori. Guide to the Software Engineering Body of Knowledge, Version 4.0. SWEBOK. IEEE Computer Society, 2024. Disponível em: https://www.computer.org/education/bodies-of-knowledge/software-engineering. p. 54.
>
> <span id="REF1">1.</span> BRASIL. História de usuário. Disponível em: https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view. Acesso em: 14 dez. 2024.

## Bibliografia

> 1. Bilheteria Digital - Histórias de Usuário. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/>. Acesso em 14 de dezembro de 2024
>
> 2. SERRANO, Milene; SERRANO, Mauricio. Requisitos - Aula 15. Apresentação de slides. FCTE (Faculdade de Ciências e Tecnologias em Engenharia): UnB, s.d.. Acesso em: 11 de dezembro 2024.


## Histórico de Versões

| Versão | Data       | Descrição | Autor     |       Revisor         |
| ------ | ---------- | --------- | --------- | --------------------- |
| `1.0`  | 13/12/2024 | Criação do documento | [Maria Helena](https://github.com/MariaCHelena) | [Victor Rodrigues](https://github.com/ViictorHugoo) |
| `1.1`  | 15/12/2024 | Adição de US | [Victor Rodrigues](https://github.com/ViictorHugoo), [Maria Helena](https://github.com/MariaCHelena), [Júlia Takaki](https://github.com/juliatakaki), [Thales Euflauzino](https://github.com/thaleseuflauzino) e [Víctor Schmidt](https://github.com/moonshinerd) | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.2`  | 17/12/2024 | Adição de novas histórias de usuário | [Maria Helena](https://github.com/MariaCHelena) | [Víctor Schmidt](https://github.com/moonshinerd) |
| `1.3` | 04/02/2025  | Ajustes pós verificação | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Rodrigues](https://github.com/ViictorHugoo)  | 
