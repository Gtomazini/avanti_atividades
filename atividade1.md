# Atividade 01
por Gabriel Tomazini

# 1. Explique, com suas palavras, o que é machine learning?
Machine Learning em palavras simples na minha concepção é uma estrutura composta de processamento de dados, tratamento de erros, redes de comunicação (ex: redes neurais) e modelos matemáticos/estatísticos que permite ao algoritmo lidar com dados e implementar uma instrução de acordo com a entrada usando
com recorrência seus próprios recursos sem a necessidade de intervenção humana em alguns dos processos o que faz ele ter essa característica de "aprendizado/learning" com o input. Assim como programas convencionais de computador ele pode lidar com input e resultar em um output com base nas instruções humanas
implementadas no desenvolvimento, mas o diferencial é essa autonomia no processo intermediário que permite ao algoritmo se autoimplementar de acordo com a situação do input.

# 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.
O algortimo de machine learning/aprendizado de máquina aprender dos dados e realiza tarefas a partir disso, para que essa etapa seja alcançado o modelo precisa ser construído com base em parametros e para isso temos o conjunto de dados de treinamento que serve como calibração do algoritmo para viabilzar o funcionamento
e passa para etapa de validação ao qual ele usa um conjunto da mesma origem do conjunto de treinamento só que reservado justamente para saber se o algoritmo está generalizando o tratamento dos de acordo com o que ele recebe, ele retorna um feedback que pode variar o formato dependendo da técnica 
utilizada de aprendizado aos quais podem ser aprendizado supervisionado e o não supervisionado e que tem o objetivo de verificar a precisão e permitir correções caso não esteja apresentando resultados satisfatórios. Passando por essas etapas de construção ele passa por uma bateria de dados de testes 
que não pertencem ao mesmo conjunto dos de treinamento e validação para comprovar a eficácia e estar apto a produção.

# 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.
A maneira de lidar com dados ausentes exige primeiro fazer uma análise contextual dos dados, pois só assim para estabelecer critérios de decisão para a escolha de uma abordagem. A primeira consideração é o peso de importância daqueles dados, por meio de métricas é possível visualizar 
o impacto do mesmo, se for baixo, o desuso desses dados é uma opção válida. Se o peso de importância(impacto) for alto, 
há uma série de abordagens para imputar (substituir valores ausentes por estimativas calculadas), pode ser feito através de média, mediana, KNN e demais recursos da matemática estatística que estão inclusos em bibliotecas como Pandas e Scikit-learn para Python. 

# 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?
Uma matriz de confusão guarda a contagem de predições corretas e incorretas feitas por um modelo de classificação, comparando-os com valores reais. Assim esses resultados são distribuídos em categorias (Verdadeiro Positivo, Falso Positivo etc) que são usados
para avaliar o desempenho de um modelo de predição com mais detalhes, possibilitando o calculo de métricas importantes sobre o desempenho do modelo:

Acurácia: $(VP + VN) / (VP + FP + VN + FN)$


Precisão: VP / (VP + FP)


Recall (Sensibilidade): VP / (VP + FN)


Especificidade: VN / (VN + FP)


F1-Score: 2 × (Precisão × Recall) / (Precisão + Recall)



Onde:

VP = Verdadeiros Positivos


FP = Falsos Positivos


VN = Verdadeiros Negativos


FN = Falsos Negativos

# 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?
Eu considero interessante dentre tantas áreas que podem se beneficiar do uso de machine learning, o campo da saúde, agricultura e manufatura onde vejo o uso benéfico e oportuno diante do avanço da internet das coisas e visão computacional nessas áreas.
