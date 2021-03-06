# Rossmann_sales_prediction

## Problema:
#####
Qual a previsão de vendas de uma rede de farmácias para as próximas 6 semanas?

## Motivação:
#####
O CFO precisava determinar o orçamento para as reformas das unidades, sendo assim, necessitava da previsão de vendas.

## Resultado:
#####
Modelo de previsão de vendas para as próximas 6 semanas com 80% de acurácia.


## Passo a passo de como cheguei no resultado esperado:
#####
Vale ressaltar que utilizei o método CRISP que trata-se de um ciclo de passos padronizados para atingir o resultado esperado o mais rápido possível e após o término do ciclo devo voltar no início objetivando atingir melhores resultados e insights.

Os passos são: 1 - Entendendo o problema de negócio; 2 - Análise descritiva dos dados; 3 - Criação do mapa mental de hipóteses ; 4 - Filtragem das linhas ; 5 - Análise exploratória dos dados ; 6 ; 7 ; 8 ; 9 e 10 - Deploy do modelo. A aplicação dos passos neste projeto podem ser visualizados abaixo e no arquivo "Notebook". 

## 1 - Entendendo o problema de negócio.

O CFO solicitou a previsão de vendas para as próximas seis semanas, mas antes de sair fazendo o projeto, deve-se entender se esta solução irá resolver o problema do solicitante (CFO).

No caso deste projeto a solicitação da previsão de vendas tinha como motivação a necessidade de determinar o orçamento que seria destinado para a reforma das unidades, sendo assim, o projeto fazia sentido e poderia seguir para o próximo passo.

## 2. Análise descritiva dos dados.

#### Atributos numéricos:
![image](https://user-images.githubusercontent.com/72674862/111880882-9e592080-898c-11eb-96a5-d0e3b2627244.png)
##### Nesta tabela podemos observar o tamanho do problema que estamos enfrentando e também se há erros de preenchimento nos dados.

#### Atributos descritivos:
![image](https://user-images.githubusercontent.com/72674862/111881399-027ce400-898f-11eb-9cef-061e60d300cb.png)
##### Nesta tabela podemos observar como estão divididos os dados sob a perspectiva de features categóricas, bem como os outliers.  

## 3. Criação do mapa mental de hipóteses.
![image](https://user-images.githubusercontent.com/72674862/111884346-edf51780-899f-11eb-8126-457798741e21.png)
##### Estas hipóteses servem de base para a análise exploratória.

## 4. Filtragem das linhas.
##### Neste passo realizo uma filtragem das linhas que não possuem dados relevantes para o problema.
Exemplo: Dia em que as lojas estavam fechadas.

## 5. Análise exploratória dos dados
##### Neste passo realizo uma análise (univariada e bivariada) mais profunda nos dados das farmácias.
##### Ganhei mais experiência sobre o negócio da empresa; gerei insights e percebi variáveis que são importantes para o modelo.

#### Análise univariada:
##### Na análise univariada identifico as distribuições dos dados e alguns padrões.

[COLOCAR IMAGEM DA RESPONSE VARIABLE]
##### Neste gráfico entendo como está a distribuição das vendas (variável resposta).

[COLOCAR IMAGEM DOS GRÁFICOS NUMÉRICOS]
##### Nestes gráficos identifico alguns padrões nos dados.

[COLOCAR IMAGEM DOS GRÁFICOS CATEGÓRICOS]
##### Nestes gráficos analiso as variáveis categóricas do meu dataset e suas distribuições.

#### Análise bivariada:
##### Na análise bivariada valido ou descarto as hipóteses que foram criadas no passo 3

Das 12 hipóteses criadas para esse projeto, segue abaixo três hipóteses validadas ou descartadas como exemplo:

H1 - Lojas com maior sortimentos deveriam vender mais.
FALSA - Lojas com MAIOR SORTIMENTO vendem MENOS.
[COLOCAR IMAGEM DOS GRÁFICOS DE ANÁLISE DA HIPÓTESE 1]




H2 - Lojas com competidores mais próximos deveriam vender menos.
FALSA - Lojas com COMPETIDORES MAIS PRÓXIMOS vendem MAIS.
[COLOCAR IMAGEM DOS GRÁFICOS DE ANÁLISE DA HIPÓTESE 2]



H
[COLOCAR IMAGEM DOS GRÁFICOS DE ANÁLISE DA HIPÓTESE 3]




**Step 01. Data Description:  Feature Engineering:  Data Filtering:**
Exploratory Data Analysis: Data Preparation: Feature selection: Machine learning modelling: Model-to-business: Deploy Model to Production: 

**10 steps: Business Understanding, Data Description, Feature Engineering, Filtering Variables,**
Exploratory Data Analysis, Data Preparation, Feature Selection, Machine Learning Modeling, Hyperparameters Fine Tuning, Translating and Interpreting the Error, and the Model Deployment.



##### Esssa tabela foi feita para poder avaliar os possíveis outliers e comportamento dos dados.
##### Escolhi tais features,
##### Usei tais modelos.
##### Fiz a seleção de features por tal modelo.
##### O modelo em produção está aqui:
##### O bot no telegram está aqui: (pode ser um gif/vídeo)


##### Primeiramente seguindo os passos do CRISP, realizei a análise descritiva dos dados.
##### 
##### 

##

##

##
##
