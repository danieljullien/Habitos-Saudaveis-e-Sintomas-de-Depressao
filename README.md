# Hábitos Saudáveis e Sintomas de Depressão

O transtorno depressivo representa um grande problema de saúde pública e é apontado como uma das principais causas de doenças e debilitações segundo a Organização Mundial da Saúde (OMS). A depressão resulta de uma interação complexa de fatores sociais, psicológicos e biológicos e, embora o acesso a diagnósticos e tratamentos esteja aumentando, muitos ainda não possuem acesso ao controle adequado dos sintomas depressivos.

Para garantir um estilo de vida saudável, a OMS recomenda a prática regular de exercícios, bem como a adoção de uma dieta saudável rica em alimentos in natura e com reduzido teor de gordura saturada, sal e açucares refinados.

Neste projeto, iremos:
1. Avaliar qual o perfil de indivíduos adultos com sintomas depressivos nos EUA
2. Investigar se hábitos saudáveis de alimentação e atividade física estão associados a menores índices de depressão nesta população.

Utilizaremos dados do National Health and Nutrition Examination Survey (NHANES) de 2006, uma pesquisa conduzida pelo National Center for Health Statistics (NCHS) do Centro de Controle e Prevenção de Doenças (Centers for Disease Control - CDC) para avaliar a saúde e nutrição de adultos e crianças dos Estados Unidos. Dados coletados incluem questões demográficas, socioeconômicas, dietéticas e relacionadas à saúde, com o componente de exame contendo medidas médicas, odontológicas, fisiológicas e exames laboratoriais. Destes dados, utilizaremos as bases de dados demográficas e de PHQ-9, HEI e PAG.

### Patient Health Questionnaire-9 (PHQ-9)

O Patient Health Questionnaire-9 (PHQ-9) é um instrumento utilizado para avaliar o grau de depressão em pacientes, que consiste em um questionário de 9 itens em que os respondentes indicam a frequência de sintomas de depressão nas duas últimas semanas, através dos dizeres "Nas últimas 2 semanas, com que frequência você ficou incomodado por algum dos problemas a seguir? (0 = nenhuma vez, 1 = menos de uma semana, 2 = uma semana ou mais e 3 = quase todos os dias)".

O escore total é calculado à partir da soma dos itens 1-9 e varia de 0 a 27, em que maiores valores do escore indicam maiores frequências de sintomas de depressão. Aqueles com pontuação maior ou igual a 5 para o escore total de PHQ-9 são considerados como tendo sintomas leves (5-9), moderados (10-14), moderadamente severos (15-19) e severos de depressão (>= 20). 

### Healthy Eating Index (HEI)

O Healthy Eating Index (HEI) é um índice de qualidade da dieta composto por 13 componentes baseado nas orientações dietéticas do governo federal americano (Dietary Guidelines for Americans). O HEI utiliza diferentes grupos alimentares para o cálculo do escore, variando de 0 a 100, em que maiores valores do escore refletem dietas mais próximas das orientações alimentares em vigor.

### Physical Activity Guidelines (PAG)

O Physical Activity Guidelines for Americans (PAG) é emitido pelo Departamento de Saúde e Serviços Humanos (U.S. Department of Health and Human Services (HHS)) e possui recomendações de atividades físicas. Este documento é utilizado em conjunto com as orientações dietéticas para americanos (Dietary Guidelines for Americans) para promover a importância de ser fisicamente ativo e seguir uma dieta saudável.

O PAG recomenda que adultos se engajem em pelo menos 150 minutos de atividades aeróbicas de intensidade moderada ou 75 minutos de atividades aeróbicas de intensidade vigorosa semanalmente. A partir dos dados coletados do NHANES, é calculado o número de minutos de atividades físicas, definido como a total minutos semanais de atividades físicas moderadas + 2*(total minutos de atividades aeróbicas vigorosas).

## Metodologia

O projeto será dividido em três etapas principais:

1. Leitura e pré-processamento dos dados.<br>
Os datasets são compostos por:
- Dados de PHQ-9 e demográficos de adultos pesquisados no NHANES 2005-2006
- Dados de HEI de PAG de crianças e adultos pesquisados no NHANES 2005-2006

2. Análise exploratória univariada para compreender a distribuição dos dados na amostra da pesquisa

3. Análise exploratória bivariada aliada a testes de hipóteses para responder identificar:
- O perfil de indivíduos adultos com sintomas depressivos nos EUA
- Possíveis associações entre hábitos saudáveis de alimentação e atividade física e índices de depressão

A pesquisa examina uma amostra selecionada à partir de amostragem complexa a fim de selecionar uma amostra representativa da população civil não institucionalizada dos EUA. Sendo assim, as análises utilizando este estudo devem ser realizadas utilizando técnicas e ferramentas que levem em conta a amostragem complexa. Neste desafio, no entanto, iremos assumir que os dados foram obtidos usando uma amostra aleatória da população de interesse e utilizaremos técnicas e ferramentas de análise usuais para amostras aleatórias para fins didáticos.
