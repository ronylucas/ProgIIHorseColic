Trabalho no âmbito da cadeira Programação e Algoritmos II, no curso de comunicação e design multimédia


Contexto:
Este trabalho tem como objetivos organizar e limpar dados fornecidos pelo dataset “Horse Colics”, intuitivamente, sobre cólicas de um grupo de 300 cavalos, e assim, demonstrar como certos sintomas e condições afetam a sobrevivência dos cavalos estudados. Para este fim, decidimos começar por filtrar os dados fornecidos, excluindo os dados com demasiada informação em falta e mantendo apenas os dados mais viáveis e produtivos para analise.
Relacionámos várias condições significativas, como a dor, para descobrir quais as situações mais propicias á morte dos dados cavalos.  Nem sempre relacionámos sintomas diretamente com a mortalidade, já que comparando as condições que mostraram melhor relação com a mortalidade umas com as outras acaba por afunilar melhor a quantidade de situações propicias, levando a uma conclusão mais concisa e certa.


Dicionário de Dados:
00. hc: ficheiro da base de dados "horse colic"
01. imp_data: dados importante selecionados
02. avgtemp: temperatura média no reto
03. maxtemp: temperatura máxima no reto
04. mintemp: temperatura mínima no reto
05. temphierarq: temperatura organizada de forma ascendente
06. temphierarq1: temperatura organizada de forma descendente
07. temp_out: dataframe agrupada para a coluna 'outcome'
08. med_outtemp: temperatura média no reto por 'outcome'
09. abddist: count dos valores de 'abdominal_distention'
10. abd_tab: dataframe agrupada para a coluna 'abdominal_distention'
11. abd_severe: cavalos com distenção abdominal severa
12. abd_mod: cavalos com distenção abdominal moderada
13. abd_lig: cavalos com distenção abdominal ligeira
14. dorcnt: count dos valores de 'pain'
15. dortab: dataframe agrupada para a coluna 'pain'
16. dormild: cavalos com dor mínima
17. dordep: cavalos com dor ligeira
18. dorext: cavalos com dor severa intermitente
19. dorsev: cavalos com dor severa contínua
20. lestab: dataframe agrupada para a coluna 'surgical_lesion'
21. yes: cavalos com lesões cirurgicas
22. no: cavalos sem lesões cirurgicas
23. med_pultemp: média da pulsação em BPM pelo 'outcome'
24. agecnt: count dos valores de 'age'


Bibliografia/ Webgrafia:
https://www.kaggle.com/datasets/uciml/horse-colic
https://pandas.pydata.org/docs/


API’s usados: 
https://www.kaggle.com/datasets/uciml/horse-colic- Dataset usado
Jupyter Notebook


Estrutura:
horse.csv: Esta folha foi a base do projeto, contém todos os dados usados.
