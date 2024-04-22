# Case 2 Data Analysis escola DNC
# Nosso case é baseado em um banco de dados onde guarda informações sobre as médias de algumas métricas para casas nos EUA, como média de salas, quartos, população, idade da casa, renda da região e preço.

# Objetivo
Nosso objetivo é identificar o quanto os dados estão dispersos com representações visuais, indicar o peso de cada valor tem sobre o outro e realizar uma predição de resultados, utilizando machine learning. 

# Conclusão
1. Foi identificado uma baixa dispersão dos valores, utilizando um histogramada e um gráfico box.
   ![image](https://github.com/GrassoRafael/predicao_de_resultados_python/assets/150485894/63c067b0-65db-4b44-b07c-78c088fe9500)
   ![image](https://github.com/GrassoRafael/predicao_de_resultados_python/assets/150485894/9dafa7ed-232c-4304-bab1-d6f82349b266)


3. Ao realizar a leitura das correlações, foi identificado que o fator "Avg_Area_Income" é o que mais impacta no preço das casas, chegamos a essa conclusão, após criar um gráfico (pairplot) para identificar correlação entre todas as variáveis da tabela, utilizando o gráfico de heatmap, pudemos numerar o quanto esse valor é correlacionado com preço.
 ![image](https://github.com/GrassoRafael/predicao_de_resultados_python/assets/150485894/3877a553-01c1-427f-88fb-9fa56cc9784c)

4. Realizamos um teste de variável onde alcançamos um valor de 91.47% de variabilidade, que explica grande parte da variação observada.
   ![image](https://github.com/GrassoRafael/predicao_de_resultados_python/assets/150485894/f3a3b440-1869-4c0a-9388-236a08c51028)

4 . Nosso modelo preditivo alcançou bons resultados em comparação com a base de teste. 
![image](https://github.com/GrassoRafael/predicao_de_resultados_python/assets/150485894/6d68f5b7-c913-47eb-8071-88ed34e635dd)

# Bibliotecas Utilizadas
1. Pandas
2. Seaborn
3. Matplotlib
4. Cufflinks
5. Chart_studio
6. Sklearn

# Feito com
  Python
  VS Code
