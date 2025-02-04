# Glossário

## Introdução

O glossário desempenha o papel de processo e produto simultaneamente. Ele serve para identificar e definir os termos característicos do domínio do problema, e sua construção contribui para a elicitação de requisitos. Optar por essa metodologia é especialmente relevante devido ao vocabulário técnico e específico de investimentos e títulos públicos que permeia o aplicativo [Tesouro Direto](https://www.tesourodireto.com.br/).

De acordo com Vazquez<a id="REF1" href="#anchor_1"><sup>1</sup></a>, para identificar os termos candidatos ao glossário, deve prestar-se atenção a termos:

- Únicos para o domínio;
- Com mais de uma definição;
- Com definição distinta do senso comum;
- Com definições não intuitivas;
- Técnicos do negócio;
- Abreviações e siglas;
- Sinônimos e antônimos.

## Glossário

Para facilitar o entendimento do aplicativo, foram reunidos e definidos termos específicos do domínio dos investimentos e títulos públicos, conforme apresentado na Tabela 1. Muitos desses termos possuem terminologia técnica e, quando necessário, explicações adicionais foram incluídas para maior clareza.

<div style="text-align: center">
<p> Tabela 1: Glossário dos termos do Tesouro Direto.</p>
</div>

| **Termo**             | **Definição**                                                                                     |
|-----------------------|-------------------------------------------------------------------------------------------------|
| **Amortização**        | Pagamento parcial ou total do valor principal de um título durante sua vigência.                 |
| **Aplicação Mínima**   | Valor mínimo necessário para realizar a compra de um título público.                             |
| **Carteira de Investimentos** | Conjunto de títulos ou ativos financeiros adquiridos por um investidor.                         |
| **Custódia**           | Serviço oferecido por instituições financeiras para guardar e administrar os títulos adquiridos. |
| **Indexado**           | Título cuja rentabilidade está atrelada a um índice econômico, como IPCA (inflação) ou Selic.   |
| **Investidor**         | Pessoa física ou jurídica que aplica recursos financeiros na compra de títulos públicos.        |
| **IPCA**               | Índice de Preços ao Consumidor Amplo, utilizado para medir a inflação no Brasil.                 |
| **Liquidez**           | Facilidade com que um título pode ser convertido em dinheiro sem perda significativa de valor.   |
| **Prefixado**          | Tipo de título cuja taxa de rentabilidade é definida no momento da compra e permanece fixa até o vencimento. |
| **Rentabilidade**      | Retorno financeiro obtido pelo investidor em função do investimento realizado.                   |
| **Resgate**            | Processo de venda ou retirada do valor aplicado em um título antes ou no vencimento.            |
| **Taxa de Administração** | Taxa cobrada por instituições financeiras para operar o investimento no Tesouro Direto.           |
| **Taxa de Custódia**   | Valor cobrado pela B3 (Bolsa de Valores) para manter e movimentar os títulos adquiridos.         |
| **Taxa Selic**         | Taxa básica de juros da economia brasileira, usada como referência para títulos atrelados à Selic. |
| **Tesouro Direto**     | Programa do governo brasileiro que permite a compra de títulos públicos por pessoas físicas pela internet. |
| **Tesouro IPCA+**      | Título público indexado ao IPCA, que garante proteção contra a inflação e retorno adicional.     |
| **Tesouro Prefixado**  | Título com taxa de retorno definida no momento da compra, ideal para quem busca previsibilidade. |
| **Tesouro Selic**      | Tipo de título público indexado à Taxa Selic, indicado para investimentos de curto prazo e maior liquidez. |
| **Título Público**     | Instrumento financeiro emitido pelo governo para captar recursos e financiar suas atividades.   |
| **Vencimento**         | Data em que o título atinge o prazo final e o valor investido é devolvido ao investidor com os juros acumulados. |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/juliatakaki">Júlia Takaki</a></font></p>
</div>

## Requisitos Elicitados

Após uma análise dos conceitos relacionados ao domínio dos investimentos e títulos públicos, foi possível identificar os requisitos descritos na Tabela 2. Cada requisito foi identificado com a sigla GLO seguida de um número, representando sua origem no glossário. Além disso, cada um foi classificado como requisito funcional (RF) ou requisito não funcional (RNF), conforme sua natureza.

<div style="text-align: center">
<p> Tabela 2: Requisitos elicitados a partir do Glossário.</p>
</div>

| **Identificador** | **Descrição do Requisito**                                                                                                                                   | **Tipo** |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| **<a id="anchor_GLO01""></a>GLO01**          | O sistema deve permitir que o usuário visualize a lista de títulos públicos disponíveis, incluindo suas características principais.                          | [RF](requisitos.md/#funcionais)       |
| **<a id="anchor_GLO02""></a>GLO02**          | O sistema deve possibilitar a compra de títulos públicos por meio de diferentes métodos de pagamento, garantindo segurança na transação.                     | [RF](requisitos.md/#funcionais)       |
| **<a id="anchor_GLO03""></a>GLO03**          | O sistema deve exibir a rentabilidade acumulada de cada título na carteira do usuário, de forma clara e atualizada.                                         | [RF](requisitos.md/#funcionais)       |
| **<a id="anchor_GLO04""></a>GLO04**          | A interface do aplicativo deve seguir padrões de acessibilidade para facilitar o uso por diferentes perfis de investidores.                                 | [RNF](requisitos.md/#não-funcionais)      |
| **<a id="anchor_GLO05""></a>GLO05**          | O sistema deve permitir o resgate antecipado de títulos, com cálculo automático do valor líquido baseado na data de resgate e na rentabilidade acumulada.   | [RF](requisitos.md/#funcionais)       |
| **<a id="anchor_GLO06""></a>GLO06**          | As transações realizadas pelo aplicativo devem ser criptografadas para garantir a proteção dos dados dos usuários.                                          | [RNF](requisitos.md/#não-funcionais)      |
| **<a id="anchor_GLO07""></a>GLO07**          | O sistema deve enviar notificações ao usuário sobre vencimentos de títulos e atualizações importantes relacionadas à sua carteira de investimentos.          | [RF](requisitos.md/#funcionais)       |
| **<a id="anchor_GLO08""></a>GLO08**          | A aplicação deve ser compatível com dispositivos móveis e navegadores modernos, garantindo desempenho e responsividade adequados.                           | [RNF](requisitos.md/#não-funcionais)      |

<div>
<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/juliatakaki">Júlia Takaki</a></font></p>
</div>

## Bibliografia

><a id="anchor_1" href="#REF1">1</a> VAZQUEZ C., SIMÕES G. Engenharia de Requisitos, 1ª edição.
>
>Termos do [Tesouro Direto](https://www.tesourodireto.com.br/), acesso em 21 de novembro de 2024.

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ---------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 21/11/2024 | Criação do documento.              | [Júlia Takaki](https://github.com/juliatakaki) |[Thales Euflauzino](https://github.com/thaleseuflauzino)|
| `1.1`  | 21/11/2024 | Ajustes fonte para autor e na bibliografia | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Victor Rodrigues](https://github.com/ViictorHugoo) |
| `1.2` | 12/12/2024  | Ajustes para pos-rastreabilidade | [Thales Euflauzino](https://github.com/thaleseuflauzino) |[Víctor Schmidt](https://github.com/moonshinerd)| 
| `1.3` | 04/02/2025  | Ajustes pós verificação | [Thales Euflauzino](https://github.com/thaleseuflauzino) |   | 