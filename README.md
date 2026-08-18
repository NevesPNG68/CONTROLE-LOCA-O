# Casa Atami — Controle de Locação

Painel de consulta alimentado exclusivamente pelo arquivo `Controle_Locacao.xlsx`.

## Atualização dos dados

1. Faça os lançamentos no Excel.
2. Salve o arquivo com o nome exato `Controle_Locacao.xlsx`.
3. Substitua a planilha no repositório.
4. Aguarde a publicação do GitHub Pages e recarregue o painel.

O `index.html` lê as abas `RESERVAS` e `DESPESAS CASA`. Não altere os nomes dessas abas nem a posição das colunas.

## Filtro por período

Os seletores **De** e **Até** aceitam qualquer intervalo mensal contínuo, como `Jan/26` até `Set/27`. Indicadores, gráficos, relatórios, reservas e despesas respeitam o intervalo escolhido. Reservas que atravessam meses têm receitas e custos rateados proporcionalmente pelas diárias de cada mês.

## Publicação

Em **Settings → Pages**, publique a branch desejada usando a pasta raiz (`/`).

## Privacidade

Em repositório público, o arquivo Excel também fica público. Antes de inserir nomes reais de hóspedes, valores ou observações pessoais, torne o repositório privado ou utilize uma fonte de dados protegida.
