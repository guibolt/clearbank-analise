# clearbank-analise

Este projeto reúne a versão final da análise feita com `pandas`. O notebook principal lê a base de transações, faz as validações e consolida os dados para gerar um resumo simples do movimento financeiro.

## Como executar

Abra o arquivo `desafio-final.ipynb` no Colab ou no Jupyter e execute todas as células em ordem. Se quiser rodar localmente, abra a pasta do projeto no VS Code, inicie o ambiente Python que preferir e siga a execução célula por célula.

## O que o notebook gera

Ao final da execução, o notebook salva `relatorio_pandas.json` com o resumo da análise e, se a célula de visualização for executada, também gera `grafico.png` com o gráfico dos valores consolidados.

## Arquivos do projeto

- `desafio-final.ipynb`: notebook com a análise principal.
- `transacoes.csv`: base de dados usada no exercício.
- `relatorio_pandas.json`: saída gerada pelo notebook.