# California Housing Prices
Preços médios de casas para distritos da Califórnia derivados do censo de 1990.
| Modelo                   | RMSE médio     | RMSE std     | R2 médio   | R2 std   |
|--------------------------|----------------|--------------|------------|----------|
| Random Forest Regressor | 50,726.738671  | 632.690707   | 0.806819   | 0.005218 |
| Ridge                   | 68,844.906567  | 455.557988   | 0.644220   | 0.005797 |
| Linear Regression       | 68,847.690269  | 460.811101   | 0.644191   | 0.005831 |
| Bayesian Ridge          | 68,850.852061  | 453.959296   | 0.644159   | 0.005754 |
| Elastic Net             | 76,780.618872  | 470.392765   | 0.557521   | 0.002349 |
| SVR                     | 118,565.716424 | 977.100337   | -0.055104  | 0.006184 |


## Conhecendo o DataSet
| **Variável**       | **Tradução**            | **Descrição**                                                                             |
| ------------------ | ----------------------- | ----------------------------------------------------------------------------------------- |
| `longitude`        | Longitude               | Medida de quão a oeste está uma casa; quanto maior o valor, mais a oeste.                 |
| `latitude`         | Latitude                | Medida de quão ao norte está uma casa; quanto maior o valor, mais ao norte.               |
| `housingMedianAge` | Idade Mediana das Casas | Idade mediana das casas em um quarteirão; valor menor indica construções mais novas.      |
| `totalRooms`       | Total de Cômodos        | Número total de cômodos em um quarteirão.                                                 |
| `totalBedrooms`    | Total de Quartos        | Número total de quartos em um quarteirão.                                                 |
| `population`       | População               | Número total de pessoas residentes em um quarteirão.                                      |
| `households`       | Domicílios              | Número total de domicílios (grupos de pessoas que vivem juntas) no quarteirão.            |
| `medianIncome`     | Renda Mediana           | Renda mediana dos domicílios em um quarteirão (medida em dezenas de milhares de dólares). |
| `medianHouseValue` | Valor Mediano das Casas | Valor mediano das casas em um quarteirão (medido em dólares).                             |
| `oceanProximity`   | Proximidade do Oceano   | Localização da casa em relação ao oceano/mar.                                             |
