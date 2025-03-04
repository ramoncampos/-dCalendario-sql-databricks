# Minhas queries


___
### 📆 <a href='https://github.com/gustavokitagawa/SQL/blob/main/Tabela-calendario-em-SQL'>Tabela calendário</a>
Aqui, eu me propus a utilizar as funções SQL do **Databricks** gerar uma tabela dimensão para calendário.

O racional para a geração desta tabela é: a partir das datas mínima e máxima de uma tabela de referência, gero uma sequência de datas com intervalo de um dia. Essa sequência é enriquecida por colunas categóricas e numéricas úteis para uma análise: ano, mês, nome do dia da semana, semestre, bimestre, trimestre entre muitas outras.

Além das funções de inteligência de tempo, complementei a query com dados categóricos como `Último ano`, `Último mês` e `Última semana` utilizando a condicional ***CASE WHEN*** em conjunto com um ***Window Function***.

<img src='screenshot_calendario_sql.png'>
