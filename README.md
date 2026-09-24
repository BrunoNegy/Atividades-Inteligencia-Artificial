# Atividades-Inteligencia-Artificial
Repositório dedicado a matéria de inteligência artificial, do 6º Semestre do curso de engenharia de software, na Universidade de Mogi das Cruzes. Atividades estas realizadas utilizando a linguagem Phyton, utilizando o Google Colab.

Lista de atividades e explicações sobre elas:

    1.Exercicios_Python: Atividade focada em iniciar a matéria e retomar os conhecimentos referente a linguagem, possui diversos conteudos diferentes, resoluções de problemas, calculos matemáticos, listas, jogos simples, e organização de números e letras. Muito útil para retomar o conteúdo e reforças os conhecimentos.
    2.Atividades_de_Data_Science_NumPY,_SciPy,_Pandas_e_Matplotlib_Bruno_Da_Silva_Negy_6ºD_6Periodo: Uma atividade focada em revisar os conteúdos de algumas bibliotecas de Python, sendo 20 exercícios de NumPy, 20 exercícios de SciPY, 20 exercícios de Pandas e 20 exercícios de Matplotlib, totalizando 80 exercícios de treino e revisão.
    3.svm_iris_aula_descritivo_Bruno_da_Silva_Negy_6D_5P: Foi realizado utilizando um arquivo .csv, criando o dataframe utilizando Pandas, e depois classificando flores pela sua característica
    4.classificacao-svm-bruno-da-silva-6d-6p: Usando o dataset envolvendo informações sobre Câncer, conseguimos classificar parcialmente o câncer entre benigno e maligno de acordo com suas características classificatórias, fazendo o aprendizado de máquina.
    5.eleicao_1936_literary_digest: O QUE FOI FEITO: 
        1. Base de dados 'LitDigestFull.xlsx' (aba '1936') carregada e inspecionada.
2. Valores ausentes/nulos e linhas estruturais ('TOTALS:') removidos.
3. Colunas desnecessárias excluídas e nomes padronizados para análise.
4. Análise Exploratória de Dados (EDA) concluída (.describe(), somatórias de votos).
5. As tabelas referentes às eleições de 1932 e 1936 foram integradas por estado, formando uma base única para permitir a comparação entre os dois anos.
6. Foram calculadas as proporções de votos da pesquisa e os erros das estimativas, comparando os resultados da pesquisa com os resultados eleitorais reais.
7. A base integrada (df_reg) foi preparada para as etapas seguintes de análise de viés e modelagem preditiva.
8. Criação de 2 gráficos de barras (Proporção de % de Votos e Volume Total de Votos).
   CONCLUSÃO — MODELAGEM PREDITIVA
A regressão linear foi utilizada para analisar se o erro observado na pesquisa de
1932 poderia ser utilizado como âncora para corrigir a previsão da pesquisa de 1936.

O modelo apresentou coeficiente de 0,3096 e intercepto de -16,0119, com R² de
0,1311. Isso indica que o erro de 1932 explica aproximadamente 13,1% da variação
observada no erro de 1936.

No conjunto analisado, a aplicação da correção baseada na regressão reduziu o erro
médio absoluto de 23,28 para 14,91 pontos percentuais. Portanto, dentro da amostra
analisada, a previsão corrigida apresentou menor erro médio do que a previsão
original da pesquisa.

Esses resultados mostram que o comportamento eleitoral observado em 1932 pode
fornecer uma informação útil para a correção das estimativas de 1936, embora o
baixo R² indique que outros fatores também contribuíram para os erros observados.


