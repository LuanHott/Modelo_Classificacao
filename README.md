# Modelo de classificação de fraudes
<p>
  <a href="https://www.linkedin.com/in/luanhteixeira/" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/800px-LinkedIn_logo_initials.png" alt="LinkedIn" width="30" height="30" style="vertical-align: middle;"/>
    <span style="vertical-align: middle; color: black;">/luanhteixeira</span>
  </a>
</p>

### Visão Geral

Esse modelo de classificação tem como objetivo classificar transações como fraudulentas ou não antes de serem concluídas.  

O notebook referente ao projeto pode ser encontrado [aqui](https://github.com/LuanHott/Modelo_Classificacao/blob/main/Classifica%C3%A7%C3%A3o_de_fraudes.ipynb)

### Ferramentas
- Python
  - Pandas: Limpeza, carregamento e análise exploratória.
  - Matplotlib: Visualização gráfica.
  - Numpy: Algumas operações matemáticas
  - scikit-learn: Modelos de machine learning

### Resultados

Após a preparação dos dados e o teste de diversos modelos, pude concluir que o modelo com maior assertividade foi o modelo Random Forest. O modelo foi testado com e sem Oversampling dos casos de fraude, que são esmagadoramente minoritários neste dataset, porém o modelo sem oversampling apresentou um melhor resultado de precisão para as operações fraudulentas. 

Os resultados dos testes do modelo vencedor são os seguintes:

Precision: 89% </br>
Recall: 68% </br>
F1-score: 75% </br>











