# Resumo de Estudos: Python, NumPy, Pandas e SQL

Este repositório contém um resumo simples com anotações de estudo para consulta rápida de sintaxes, comandos e exemplos básicos de Python, NumPy, Pandas e SQL.

## Acesso

* [Visualizar versão online](https://drive.google.com/file/d/1-YXq8M1qBR96Vu8n1Bv7dBoVO3IpP3Xo/view?usp=sharing)

---

## Tópicos Abordados

### 1. Python
* Operadores lógicos (`and`, `or`, `not`), tipos primitivos (`int`, `float`, `bool`, `str`) e entrada de dados (`input`).
* Formatação de exibição, máscaras de dados e `f-strings`.
* Métodos de manipulação e verificação booleana de strings (`upper`, `lower`, `title`, `find`, `count`, `replace`, `split`, `join`, `strip`, `isdigit`, `isalpha`, entre outros).
* Estruturas de repetição (`for`, `range`, `while`, `break`).
* Leitura e escrita em arquivos de texto (`open`, `read`, `write`, `close`).
* Funções (`def`), parâmetros opcionais, argumentos nomeados (`kwargs`) e anotação de tipo de retorno.
* Estruturas de dados: listas, *list comprehension*, dicionários, tuplas e conjuntos (`set`).
* Importação de pacotes e uso básico de bibliotecas nativas (`math`, `random`, `calendar`, `datetime`).

### 2. NumPy
* Criação de arrays unidimensionais e bidimensionais (`np.array`) e especificação de tipo (`dtype`).
* Indexação, fatiamento (*slicing*) e operações matemáticas elemento a elemento.
* Funções estatísticas básicas (`mean`, `sum`, `std`).
* Remodelagem (`reshape`), concatenação (`concatenate`) e divisão de arrays (`array_split`).
* Seleção condicional com máscaras booleanas e `np.where`.

### 3. Pandas
* Criação e manipulação de `Series` e `DataFrame`.
* Inspeção de estrutura e estatísticas descritivas (`dtypes`, `describe`, `shape`, `columns`, `value_counts`, `unique`, `nunique`, `size`, `var`, `quantile`).
* Definição, renomeação e exclusão de índices (`set_index`, `rename`, `drop`, `idxmax`, `idxmin`) e uso do parâmetro `inplace`.
* Seleção e filtragem de linhas e colunas utilizando `loc`, `iloc`, `query` e condições múltiplas.
* Identificação e tratamento de valores nulos (`isna`, `dropna`, `fillna`) e duplicados (`duplicated`, `drop_duplicates`).
* Criação e transformação de colunas (`apply`, `insert`, `assign`, `map`, `astype`) e divisão em faixas/quartis (`qcut`).
* Agrupamento e agregação de dados (`groupby`, `agg`), tabelas dinâmicas (`pivot_table`) e reestruturação de tabelas (`melt`).
* Combinação de DataFrames (`merge`, `concat`) e cálculos de deslocamento e variação (`shift`, `diff`, `pct_change`).
* Diferença entre cópia e visualização de dados (`SettingWithCopyWarning`), uso do tipo `Category` e diferença de retorno entre `Series` e `DataFrame`.

### 4. SQL
* Consultas básicas (`SELECT`, `FROM`, `WHERE`, `DISTINCT`, `ORDER BY`).
* Operadores relacionais, lógicos (`AND`, `OR`, `NOT`), matemáticos e de intervalo (`BETWEEN`).
* Filtros de padrão de texto com `LIKE` (`%` e `_`) e verificação de valores nulos (`IS NULL`, `IS NOT NULL`).
* Junção de tabelas: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL JOIN`, `NATURAL JOIN` e `SELF JOIN`, além do uso de apelidos (`AS`).
* Funções de agregação (`COUNT`, `MAX`, `MIN`, `AVG`, `SUM`), agrupamento (`GROUP BY`) e filtragem de grupos (`HAVING`).
* Subconsultas simples e correlatas nas cláusulas `WHERE`, `FROM` e `SELECT` utilizando `IN`, `ALL`, `ANY`, `EXISTS` e `NOT EXISTS`.
* Operações de conjunto (`UNION`, `UNION ALL`, `INTERSECT`, `EXCEPT`).
