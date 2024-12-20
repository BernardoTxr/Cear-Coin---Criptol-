## DATATHON FGV - MOEDAS DIGITAIS
#### Repositório criado para a equipe CearáCoin, os criadores do Criptolé!
#### Bernardo Teixeira - USP
#### Júlia Wayss - UNIFOR
#### João Pedro Brasil - UNIFOR
#### Lucas Lustosa - UNIFOR

## Quem é Criptolé
A apresentação do Criptolé, um Portfolio Manager que busca democratizar o investimento em criptomoedas, pode ser vista na apresentação 'Criptolé - FGV DATATHON.pdf' na raiz do repositório.

## Descrição do Repositório:
- Em /data/fontes_primarias estão os datasets de onde buscamos alguns dados utilizados na análise. No entanto, muitos outros dados foram obtidos diretamente da API do YahooFinance. 
- Em /data/datasets_criados estão datasets intermediários que foram criados durante o processo. Os 'artificiais' se referem a um conjunto de dados criados para testar se o comportamento estava de acordo com o esperando. Os 'indicadores' se referem aos indicadores utilizados. Os 'merged' são a união dos dois anteriores.
- Em /gráficos/resultados, estão alguns gráficos intermediários que foram obtidos. Antes da escolha da renda fixa, acreditávamos que o Ouro seria mais característico do conservador, o que, depois, percebemos ser um erro. Por isso, alguns gráficos antigos possuem a comparação com Ouro, Ibovespa e Bitcoin. 
- Em /notebooks, estão os notebooks usados para a análise do resultado, para testes, para a criação dos datasets e para a criação dos gráficos usados na apresentação. Ainda, estão todas as versões do Criptolé, desde as iniciais até as usadas na apresentação. Ainda, algumas implementações mais recentes do Criptolé que envolviam e-greedy (uma maneira de melhorar a exploração do modelo) e outras versões que buscavam utilizar as métricas estatísticas sugeridas no final da apresentação (value at risk, sharpe ratio) foram também implementadas, mas não analisadas para a apresentação. A equipe CearáCoin acredita que a interpretação desses resultados é o próximo passo dessa pesquisa. 

## Como replicar os resultados?
Para replicar os resultados, utilize o notebook 'criptolé_oficial'. O tracking das execuções realizadas foram feitas no MLflow (uma ferramenta de gerenciamento de ciclo de vida de algoritmos de Inteligência Artificial). Essa ferramenta é necessária para executar o treinamento e teste do modelo e deve ser instalada via pip (pip install mlflow).

Por fim, testes (seguindo a ordem cronológica), podem ser realizados no notebook 'testes.ipynb' após o treinamento do Criptolé. 

