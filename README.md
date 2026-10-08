# Painel E Sousa Arte & Papel

Painel de vendas, estoque e financeiro da loja E Sousa Arte & Papel, feito para acompanhar TikTok Shop, Shopee, Etsy e venda local. Não tem login nem agenda.

## O que tem

- **Resumo**: faturamento, lucro líquido, previsão se pagar o que está pendente, valor a receber e comparação com o mês anterior.
- **Vendas**: lançamento por canal, taxa da plataforma, frete, "a receber" e "recebido". Cada venda desconta do estoque sozinha.
- **Estoque**: custo, preço, margem, quantidade, alerta de reposição, entradas de compra e ajuste de contagem. Arquivos digitais (Etsy) ficam sem controle de estoque.
- **Despesas**: categorias, pagas e a pagar, com gráfico de onde o dinheiro vai.
- **Histórico**: faturamento mês a mês por canal, tabela com lucro e ranking de produtos e canais no período.
- **Configurações**: taxa de cada canal, categorias, backup, exportação em CSV e importação de produtos e de vendas de meses anteriores (CSV ou Excel).

## Importar meses anteriores

Em Configurações, use "Importar vendas de meses anteriores" com o relatório de pedidos baixado da plataforma. O painel reconhece colunas como data do pedido, produto, quantidade, preço ou total, taxa, frete e número do pedido, e mostra o que entendeu antes de importar. Importar o mesmo arquivo duas vezes não duplica as vendas.

Vendas e entradas anteriores à data de "Estoque contado em" de um produto não mexem na quantidade em estoque. Assim dá para lançar meses antigos sem bagunçar o estoque de hoje.

## Onde os dados ficam

Este repositório guarda só a página, sem nenhum dado da loja. Quando o painel roda como artefato no Claude, os dados ficam salvos no banco do próprio artefato. Abrindo o `index.html` fora do Claude, os dados ficam só no navegador daquele aparelho, então faça backup em Configurações.

## Arquivos

- `index.html`: o painel inteiro, em um único arquivo.
