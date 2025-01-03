## Удержание и прибыль: анализ и персонализация покупательской активности в интернет-магазине

### Цель проекта

Анализ покупательской активности клиентов онлайн-магазина, с целью выявления факторов, влияющих на прибыль, и разработки стратегии для повышения активности и прибыли от клиентов


### Задачи проекта

1. Изучить данные.
2. Подготовить данные.
3. Исследовательский анализ данных, с фокусом на поведение постоянных клиентов (с покупательской активностью не менее трёх месяцев).
4. Корреляционный анализ: будет проведён корреляционный анализ признаков в количественной шкале, чтобы выявить факторы, влияющие на покупательскую активность и прибыль постоянных клиентов.
5. Моделирование: четыре модели классификации (KNeighborsClassifier, DecisionTreeClassifier, LogisticRegression, SVC) будут обучены с использованием пайплайнов, с подбором гиперпараметров и выбором лучшей модели по выбранной метрике.
6. Анализ важности признаков: с помощью метода SHAP будет оценена важность признаков для лучшей модели, чтобы определить ключевые факторы, влияющие на покупательскую активность постоянных клиентов.
7. Сегментация покупателей: будет выполнена сегментация покупателей с использованием результатов моделирования и данных о прибыльности, выбран один сегмент для дополнительного анализа и разработки предложений по повышению его покупательской активности.
8. Рекомендации по персонализации: на основе анализа и моделирования будут предложены конкретные рекомендации по персонализации предложений для выбранного сегмента



### Навыки и инструменты

- matplotlib.pyplot
- numpy
- pandas
- python
- seaborn
- phik
- sklearn.model_selection
- sklearn.linear_model
- sklearn.neighbors
- sklearn.tree
- sklearn.svm
- sklearn.preprocessing
- sklearn.metrics
- scipy.stats
- sklearn.impute
- sklearn.pipeline
- sklearn.compose
- import shap