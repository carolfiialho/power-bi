# Power-BI-PIB

Dashboard feito no Power BI, com as informações de PIB (Produto Interno Bruto) e qtd populacional dos estados brasileiros entre 2002 e 2020.

>***ATENÇÃO: Não tomem como verdades os dados fornecidos, o intuito deste projeto foi obter dados de forma simples, brincar e explorar opções de análises.***

### Passo 1:
Coletei os dados através de duas consultas no Google Cloud Plataform, de tabelas liberadas pela [@basededados](https://github.com/basedosdados) 
- A primeira consulta coletou os valores de PIB dos estados brasileiros entre 2002 e 2020.
- A segunda consulta coletou os valores populacionais das cidades dos estados brasileiros de 2002 e 2020.
- Foi criado uma nova coluna chave para obter a relação Muitos para Muitos em ambas consultas.
- Foi criado uma nova tabela sumarizada (através da segunda consulta), para obter os valores populacionais por estados brasileiros e uma coluna com o valor de Renda Per Capita de cada estado (A renda per capita é calculada através da divisão do PIB pelo valor populacional do mesmo local), criando a relação de 1:1 com a primeira consulta.

## Relação entre as tabelas criadas:
<img width="1421" src="https://github.com/carolfiialho/power-bi/blob/main/relacao_tabelas.png">

### Passo 2:
Após as relações criadas, doi desenvolvido as visualizações básicas dos dados.
- As primeiras visualizações criadas foram os gráficos de disperção para a Renda Per Capita por estado, PIB estadual e Qtd populacional estaduais.
- Logo após foi criado os gráficos de linha para a verificação da Renda Per Capita brasileira anual, PIB brasileiro anual e População brasileira anual.
- E por fim 3 cartões com as informações das variações de valores entre o ano de 2002 e 2020 sobre a Renda Per Capita brasileira anual, PIB brasileiro anual e População brasileira anual.

- ## Visualização do dashboard

- <img width="1421" src="https://github.com/carolfiialho/power-bi/blob/main/pbi_pib.png">

## Insights:

Quando finalizado as visualizações, já podemos perceber vários insights que estes dados nos forneceram.

1- A Renda Per Capita no Estado do Distrito Federal é maior que São Paulo, o estado que possui o Maior PIB e População do Brasil.

2- O aumento do PIB no estado de São Paulo foi maior em comparação com os outros estados.

3- O aumento populacional brasileiro, se manteve estável em todos os estados, sem uma grande variação em algum lugar específico.

## Futuras análises e ideias:

Ter essa visualização da quantidade populacional, Renda Per Capita e PIB estadual, trouxeram ideias de analisar os contextos dos estados brasileiros e talvez destrinchar as informações em:
- Qual a diferença do PIB de São Paulo para o segundo maior PIB de estado brasileiro?
- Qual a diferença de Renda Per Capita do Distrito Federal para o segundo maior estado com Renda Per Capita?
- Onde houve o maior crescimento populacional entre 2002 e 2020?
- Qual a quantidade de empresas privadas em cada estado?
- Qual a quantidade de novas empresas privadas em cada estado?
- Qual a % da população que completou ensino superior?
- Qual a % da população que completou ensino médio?
- Qual a % da população que está desempregada? Qual estado tem a maior taxa de desemprego? É o mesmo estado que tem a menor Renda per Capita?

Com essas visões e talvez até outras mais, conseguiríamos entender o porque certos lugares possuem a Renda Per Capita ou PIB maiores que outros.
Além do conhecimento "geral", de que sabemos que os grandes polos se concentram no Sudeste e Sul do país e consequentemente atraem mais empregos, mais renda e uma quantidade maior populacional.




  






