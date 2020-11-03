# Models 

1. clustering: определение лояльных покупателей. **К средних** (sklearn - Kmeans). 
2. classification: распределить новые точки продаж по имеющимся сегментам. **Гадиентный бустинг** (sklearn - Gradient boosting classifier).
3. time_series: прогнозирование количества визитов в магазины. **sARIMA** (statsmodels - sARIMA). 
4. lookalike: выделение из общего массива респонденов максимально похожих на заданную группу. **Positive-Unlabled классификация** (sklearn - LogisticRegression). 
5. retail_uplift: оценка эффективности взаимодействия с покупателем. **Градиентный бустинг на деревьях** (lightgbm - LGBMClassifier). 
6. association_rules: определить комплементарные товары. **Apriori** (mlxtend - apriori, association_rules).
