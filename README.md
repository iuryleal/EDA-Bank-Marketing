# Português - Análise Exploratória de Dados - Bank Marketing

Com a finalidade de entender melhor o perfil dos clientes para potencializar a venda de um produto de investimento, a área de marketing criou uma campanha selecionando alguns clientes para realizar a oferta. A duração da campanha foi de 3 meses e abrangeu todo o Brasil. 

Finalizada a campanha, o marketing disponibilizou a base de dados e solicitou uma análise do perfil dos clientes à área de Analytics. A expectativa é que esse estudo forneça informações suficientes para que as próximas campanhas sejam direcionadas para o público mais propenso a comprar o produto de investimento.

Para identificar o perfil dos clientes, foi realizada uma análise exploratória dos dados com Python – utilizando as bibliotecas pandas, numpy, seaborn e matplotlib.

Aqui, estão alguns insights e oportunidades de melhorias iniciais:

Variável: Cliente comprou titulo?
- Ligeira maioria da base não comprou o título (50,66%)
- Qual a meta?
- Qual benchmark?

Variável: Faixa etária
- 32-39 corresponde à maior categoria de idade da base (27,07%). Isso é interessante devido à maior probabilidade de possuir renda suficiente para investir?
- 25-53 corresponde a cerca de 78,35% da base
- Qual a meta?
- Quais os benchmarks?

Variável: Profissão
- Administrador corresponde à maior categoria da base (35,13%). Dado interessante devido ao nivel de consciência, teoricamente, mais elevado deste tipo de profissão?
- Administrador, Operário, Técnico e Serviços Gerais correspondem a 76,27% da base
- Qual a meta?
- Quais os benchmarks?

Variável: Escolaridade
- Ensino médio é a categoria mais prevalente na base (48,71%).
- Ensino médio + ensino superior correspondem a 82,23% da base.
- O que houve para, quase, 5% da base não informar os dados de escolaridade? É possível identificar causa raíz para diminuir este indicador?
- Qual a meta?
- Quais os benchmarks?

Variável: Estado Civil
- 89.09% da base é solteiro ou casado
- A base é formada, majoritariamente, por casados (56,47%). Ser casado é melhor pois a familia, teoricamente, tem duas fontes de renda e, consequentemente, maior possibilidade de investir?
- Qual a meta?
- Qual o benchmark?

Variável: Cliente devedor?
- Quase 100% da base NÃO é cliente devedor. Qual critério de escolha destes clientes? Foi intencional?
- É interessante que maior parte da base não seja devedora?
- Qual a meta?
- Qual benchmark?

Variável: Saldo em conta corrente
- Faixa com 1-1956 de saldo_conta_corrente possui maior concentração na base (74,43%). Isso é desfavorável? Visto que menor renda implica em menor probabilidade de alocar recurso em investimento?
- Qual a meta?
- Qual o benchmark?

Variável: Tem hipoteca?
- Maior parte da base NÃO tem hipoteca (54,32%)
- Isso é bom ou ruim?
- Qual a meta?
- Qual benchmark?
  
Variável: Tem empréstimo?
- A base, majoritariamente, NÃO possui emprestimo (88,36%). Isso é bom porque eles tem mais dinheiro para investir? Isso é bom para argumentar que eles podem pegar algum emprestimo para financiar algum sonho/projeto e pagar com rendimento do investimento?
- Qual a meta?
- Qual o benchmark?
  
Variável: Qtd Ligações Feitas
- Realizar até 4 ligações foi suficiente para atingir 82,42% da base; investir em mais ligações do que isso só consegue atingir 17,58% da base. O investimento em mais de 4 ligações se justifica?
- Qual a meta?
- Qual benchmark?

# English - EDA (Exploratory Data Analysis) - Bank Marketing

With the purpose of better understanding the customer profile to enhance the sales of an investment product, the marketing department created a campaign selecting some customers to make the offer. The campaign lasted for 3 months and covered the entire Brazil.

Once the campaign was finished, the marketing department provided the database and requested an analysis of the customer profile from the Analytics department. The expectation is that this study will provide enough information for future campaigns to be targeted towards the audience most likely to buy the investment product.

To identify the customer profile, an exploratory data analysis was conducted using Python - utilizing the libraries pandas, numpy, seaborn, and matplotlib.

Key highlights and questions:

Variable: Did the customer buy the investment product?

A slight majority of the database did not buy the product (50.66%).
What is the target?
What are the benchmarks?

Variable: Age Group
- The age group 32-39 corresponds to the largest category in the database (27.07%). Is this interesting due to the higher likelihood of having sufficient income to invest?
- The age group 25-53 corresponds to approximately 78.35% of the database.
- What is the target?
- What are the benchmarks?

Variable: Occupation
- Administrator corresponds to the largest category in the database (35.13%). This is interesting due to the theoretically higher level of awareness of this type of profession?
- Administrator, Worker, Technician, and General Services correspond to 76.27% of the database.
- What is the target?
- What are the benchmarks?

Variable: Education
- High school is the most prevalent category in the database (48.71%).
- High school + higher education correspond to 82.23% of the database.
- What caused almost 5% of the database not to inform their education data? Is it possible to identify the root cause to decrease this indicator?
- What is the target?
- What are the benchmarks?

Variable: Marital Status
- 89.09% of the database is single or married.
- The database is predominantly composed of married individuals (56.47%). Is being married better because theoretically, the family has two sources of income and consequently, a higher possibility of investing?
- What is the target?
- What is the benchmark?

Variable: Is the customer a debtor?
- Almost 100% of the database is NOT a debtor. What criteria were used to choose these customers? Was it intentional?
- Is it interesting that the majority of the database is not a debtor?
- What is the target?
- What is the benchmark?

Variable: Balance in current account
- The range with 1-1956 balance in the current account has the highest concentration in the database (74.43%). Is this unfavorable? Given that lower income implies a lower probability of allocating resources in investment?
- What is the target?
- What is the benchmark?

Variable: Has a mortgage?
- The majority of the database does NOT have a mortgage (54.32%).
- Is this good or bad?
- What is the target?
- What is the benchmark?

Variable: Has a loan?
- The database, mostly, does NOT have a loan (88.36%). Is this good because they have more money to invest? Is this good to argue that they can take a loan to finance a dream/project and pay with the investment return?
- What is the target?
- What is the benchmark?

Variable: Number of Calls Made
- Making up to 4 calls was enough to reach 82.42% of the database; investing in more calls than this can only reach 17.58% of the database. Does investing in more than 4 calls justify itself?
- What is the target?
- What is the benchmark?
