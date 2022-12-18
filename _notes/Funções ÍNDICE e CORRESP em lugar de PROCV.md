## Contexto
	- As funções **`ÍNDICE`** e **`CORRESP`** podem ser utilizadas em conjunto em substituição à função `PROCV` e à fórmulas matriciais do Excel;
	- Tal utilização torna as planilhas mais leves e os cálculos mais rápidos.
## Função **`ÍNDICE`**
	- A função `ÍNDICE` retorna o valor que se encontra em determinada linha e coluna de uma matriz de dados como por exemplo:
		-
		  ```
		  =ÍNDICE(A2:G618;3;6) 
		  ```
	- Este exemplo retorna o valor que se localiza entre as células `A2` e `G618` na coluna `3` e linha `6`.
## Função **`CORRESP`**
	- A função `CORRESP` retorna a **posição** de um determinado valor em uma linha ou uma coluna, como por exemplo:
		-
		  ```
		  =CORRESP(J3;A1:A618;0)
		  ```
	- Neste exemplo, `J3` é o valor que está sendo procurado, `A1:A618` é o _intervalo de dados_ dentro da coluna A em que se deseja localizar o valor, e o parâmetro `0` na terceira posição indica que se deseja retornar **_correspondências exatas_**.
## Combinando **`ÍNDICE`** + **`CORRESP`**
	- Como mencionado acima, `ÍNDICE` retorna o \*\*valor de uma célula\*\* em uma determinada posição e `CORRESP` determina a \*\*posição de um valor\*\* dentro de um intervalo de dados. Assim, podem ser usados da seguinte forma juntos:
		-
		  ```
		  
		  =ÍNDICE(A2:G618;CORRESP(358;A2:A618;0);CORRESP(“Vendedor”;A1:G1;0))
		  ```
	- Neste exemplo, `A2:G618` é a definição do \*\*intervalo de células\*\* em que se deseja localizar um valor, `358` é o valor a se localizar na coluna referenciada por `A2:A618` e `Vendedor` é a coluna que se deseja localizar entre o intervalo de colunas `A1` e `G1`.
	- Ou seja, `ÍNDICE` determina o **local** em que será realizada a pesquisa, e `CORRESP` identifica a **linha** e a **coluna** que se deseja identificar no intervalo.