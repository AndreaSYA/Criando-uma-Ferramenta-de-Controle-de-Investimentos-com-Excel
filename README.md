# Criando-uma-Ferramenta-de-Controle-de-Investimentos-com-Excel
Planilha de simulação de investimentos em Fundos Imobiliários (FIIs), desenvolvida no Excel. Permite calcular o patrimônio futuro, estimar dividendos mensais e distribuir aportes conforme o perfil do investidor, utilizando fórmulas financeiras e funções de busca.
Pergunta	                                                   Onde aparece              	O que faz
Qual é a sugestão de investimento mensal com base no salário?	  INVEST!D14	          Calcula 30% do salário informado.
Quanto investir por mês e durante quantos anos?	                INVEST!D17:D18       	Recebe os parâmetros do investimento.
Qual é o patrimônio acumulado no período escolhido?	            INVEST!D20	          Calcula o valor futuro dos aportes.
Quanto esse patrimônio pode gerar em dividendos mensais?	      INVEST!D21	          Multiplica o patrimônio pela taxa de rendimento da carteira.
Quanto posso acumular em diferentes períodos?                  	INVEST!C24:D28	      Compara os cenários de 2, 5, 10, 20 e 30 anos.
Como distribuir meu aporte entre as categorias de FIIs?        	INVEST!B32:D42	      Apresenta o perfil, os percentuais sugeridos e os valores correspondentes.
 O que foi alterado em relação à ferramenta original do Expert?

Desenvolvi minha própria versão da ferramenta de simulação de investimentos, seguindo a mesma estrutura e os passos apresentados pelo Expert, mas adaptando alguns elementos à minha maneira.

As principais diferenças foram:

Organização da planilha:** alterei o nome da aba principal de `APP` para `INVEST`.
-Referências nas fórmulas:** na versão original, algumas fórmulas utilizam intervalos nomeados, como `aporte`, `patrimonio`, `qtd_anos` e `taxa_mensal`. Na minha versão, utilizei referências diretas às células, como `D17`, `D18`, `D19` e `D20`.
-Parâmetros iniciais:** alterei o salário utilizado como exemplo de R$ 2.000 para R$ 4.200.
- Distribuição dos investimentos:** mantive os três perfis de investidor e as seis categorias de FIIs, mas alterei a distribuição percentual do perfil moderado entre FOFs e Desenvolvimento.
- Adaptação da estrutura:** mantive a lógica principal dos cálculos de patrimônio acumulado, dividendos mensais e distribuição dos aportes, personalizando a organização da planilha.

O projeto foi desenvolvido com o objetivo de praticar os conhecimentos de Excel, incluindo fórmulas financeiras, funções de busca, referências entre células e organização de dados em tabelas auxiliares.
