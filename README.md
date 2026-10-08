# Casa Atami — Controle de Locação

Painel de consulta alimentado exclusivamente pelo arquivo `Controle_Locacao.xlsx`.

## Atualização dos dados

1. Faça os lançamentos no Excel.
2. Salve o arquivo com o nome exato `Controle_Locacao.xlsx`.
3. Substitua a planilha no repositório.
4. Aguarde a publicação do GitHub Pages e recarregue o painel.

O `index.html` lê as abas `RESERVAS` e `DESPESAS CASA`. Não altere os nomes dessas abas nem a posição das colunas.

## Feriados na agenda

A agenda consulta automaticamente os feriados nacionais do Brasil para o ano exibido. A fonte principal é a BrasilAPI, com fallback para Nager.Date; os resultados ficam em cache local por até 7 dias e continuam disponíveis quando a aplicação estiver temporariamente offline. Feriados municipais e estaduais não são incluídos sem uma configuração de localidade.

## Filtro por período

Os seletores **De** e **Até** aceitam qualquer intervalo mensal contínuo, como `Jan/26` até `Set/27`. Indicadores, gráficos, relatórios, reservas e despesas respeitam o intervalo escolhido. Reservas que atravessam meses têm receitas e custos rateados proporcionalmente pelas diárias de cada mês.

## Publicação

Em **Settings → Pages**, publique a branch desejada usando a pasta raiz (`/`).

## Privacidade

Em repositório público, o arquivo Excel também fica público. Antes de inserir nomes reais de hóspedes, valores ou observações pessoais, torne o repositório privado ou utilize uma fonte de dados protegida.
