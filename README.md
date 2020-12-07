# Models description: 

1. association_rules: определить комплементарные товары. **Apriori** ([mlxtend - apriori, association_rules](http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/)).
2. classification: распределить новые точки продаж по имеющимся сегментам. **Гадиентный бустинг** ([sklearn - Gradient boosting classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)).
3. clustering: определение лояльных покупателей. **К средних** ([sklearn - Kmeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)). 
4. lookalike: выделение из общего массива респонденов максимально похожих на заданную группу. **Positive-Unlabled классификация** ([PU](https://roywrightme.wordpress.com/2017/11/16/positive-unlabeled-learning/) + [sklearn - LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)). 
5. time_series: прогнозирование среднего чека покупки в магазине. **sARIMA** ([statsmodels - sARIMA](https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html)). 
6. uplift: оценка эффективности взаимодействия с покупателем. **Градиентный бустинг** ([lightgbm - LGBMClassifier](https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html)). 
