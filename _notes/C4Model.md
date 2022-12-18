## Modelo C4
created-at:: 1627000487247
updated-at:: 1627000487247
	- O **Modelo C4** foi criado para ajudar as equipes de desenvolvimento de software a descreverem e comunicarem a [[arquitetura de software]], tanto durante sessões de
	  created-at:: 1627000489197
	  updated-at:: 1627000489197
	  *design* quanto durante a documentação de uma base de código.
	- É uma forma de criar *mapas* do código criado, em vários níveis de detalhe, da mesma maneira que alguém poderia usar o Google Maps para aplicar ou retiram *zoom* a uma área de um mapa em que se tenha interesse.
	  created-at:: 1627000489211
	  updated-at:: 1627000489211
### Pontos Principais
created-at:: 1627000487263
updated-at:: 1627000501866
	- A criação de diagramas de software foi reduzida como resultado da mudança para o uso das metodologias ágeis. Quando diagramas são criados, eles geralmente são confusos e pouco claros;
	  created-at:: 1627000495711
	  updated-at:: 1627000495711
	- O modelo C4 consiste em um conjunto hierárquico de diagramas de arquitetura de software para **contexto**, **containers**, **componentes** e **código**;
	  created-at:: 1627000495715
	  updated-at:: 1627000498322
	- A hierarquia dos diagramas C4 fornece diferentes níveis de abstração, cada um dos quais é relevante para um público diferente;
	  created-at:: 1627000498327
	  updated-at:: 1627000500099
	- Evite a ambiguidade em seus diagramas incluindo uma quantidade suficiente de texto, bem como uma chave/legenda para a notação utilizada.
	  created-at:: 1627000501860
	  updated-at:: 1627000505523
### Níveis do modelo C4
created-at:: 1627000502769
updated-at:: 1627000503398
	- #### Nível 1: O diagrama de contexto do sistema
	  created-at:: 1627000508741
	  updated-at:: 1627000508741
		- O nível 1, um diagrama de contexto do sistema, mostra o sistema de software que você está construindo e como ele se encaixa no mundo em termos das pessoas que o utilizam e dos outros sistemas de software com os quais ele interage.
		  created-at:: 1627000543915
		  updated-at:: 1627000543915
	- #### Nível 2: O diagrama de *container*
	  created-at:: 1627000527745
	  updated-at:: 1627000557804
		- O nível 2, um diagrama de *container*, amplia o sistema de software e mostra os *containers* (aplicativos, armazenamentos de dados, *microservices*, etc.) que compõem esse sistema de software. As **decisões de tecnologia** também são uma parte fundamental desse diagrama.
		  created-at:: 1627000562087
		  updated-at:: 1627000563491
	- #### Nível 3: O diagrama de componentes
	  created-at:: 1627000576836
	  updated-at:: 1627000576836
		- O nível 3, um diagrama de componentes, amplia um *container* individual para mostrar os componentes dentro dele. Esses componentes devem mapear para abstrações reais (por exemplo, um agrupamento de código) em sua base de código.
		  created-at:: 1627000576843
		  updated-at:: 1627000577386
	- #### Nível 4: O código
	  created-at:: 1627000580116
	  updated-at:: 1627000580116
		- Finalmente, se você realmente quiser ou precisar, você pode ampliar um componente individual para mostrar como esse componente é implementado.
		  created-at:: 1627000585515
		  updated-at:: 1627000585515
### Ver também:
created-at:: 1627000603368
updated-at:: 1627000603368
	- [Site oficial do C4Model](https://c4model.com/)
	  created-at:: 1627000579272
	  updated-at:: 1627000594250
	- [O modelo C4 de documentação para Arquitetura de Software](https://www.infoq.com/br/articles/C4-architecture-model/), na InfoQ.
	  created-at:: 1627000594252
	  updated-at:: 1627000594252