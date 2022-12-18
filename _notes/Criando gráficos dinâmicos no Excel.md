- Um **gráfico dinâmico** do Excel (conhecido em inglês pela terminologia _`rolling chart`_ é um gráfico onde os dados exibidos representam os últimos `n` meses, ou `n` valores, mas com a diferença de que, num gráfico deste tipo, os dados são atualizados automaticamente.
- Normalmente são representados os últimos 12 meses em um gráfico dinâmico, e existem várias formas de criar um desses, mas a mais simples que encontrei, já que não usa funções mais avançadas como **`ÍNDICE`** ou **`DESLOC`**, e sim funções mais simples, é seguindo os passos abaixo:
	-
	  1.  Se os dados a partir dos quais o gráfico dinâmico deve ser gerado não estão em uma **tabela do Excel**, é necessário transformar os dados em uma tabela primeiro. Para isso, selecione todo o _range_ e, com os dados selecionados, a partir da guia **Inserir**, escolha a opção **Tabela** (ou use o atalho **`CTRL + ALT + T`**;
	  collapsed:: false
	-
	  2.  Com a tabela criada, na guia **Design da Tabela**, atribua um nome à tabela (exemplo: **tabDados**);
	-
	  3.  O próximo passo é calcular a maior data existente na tabela de dados. Como exemplo, vamos dizer que a tabela **tabDados** contém uma coluna chamada **Data**, com o formato **mmm/aa**. Em uma célula à parte, utilizar a fórmula **`=MÁXIMO(tabDados[Valor])`**. Suponha que o valor gerado seja **dez/20**;
	-
	  4.  Agora, deve-se calcular o **mês anterior** ao maior mês. Na célula imediatamente acima àquela em que foi digitada a fórmula do passo anterior, utilizar a fórmula **`=DATAM(data;-1)`**. Seguindo o exemplo do passo anterior, teremos **nov/20**;
	-
	  5.  Usando a **alça do navegador** do Excel, arraste a fórmula do passo anterior para cima, até obter a quantidade de meses que deseja no gráfico dinâmico;
	-
	  6.  Agora adicione um **cabeçalho** à esta coluna com as datas (por exemplo, **Período**);
- Daqui por diante o passo-a-passo envolve criar a(s) coluna(s) extra(s) que farão parte dos dados do gráfico, utilizando por exemplo, as [[Funções ÍNDICE e CORRESP em lugar de PROCV]] e, é claro, inserir o gráfico propriamente dito, que será atualizado sempre que novas linhas com datas posteriores forem inseridas nos dados da tabela original.