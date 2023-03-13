# Playground Series - Season 3, Episode 3
## Tabular Classification with an Employee Attrition Dataset
### Проведен разведовательный анализ данных
1. Построены графики распределения категориальных и непрерывных признаков
2. Установлены парные связи между признаками и удалены колонки, которые имеют сильную линейную связь
3. Работа с выбросами. 
4. Энкодинг категориальных признаков через **OrdinalEncoder**
### Обучение модели и предсказание
1. Были обучены **CatBoostClassifier**, **LGBMClassifier**, **XGBClassifier**, метрика **ROC-AUC**, **n_estimators** = *1000*, **learning_rate** = *0.01*
2. Выведены **Feature Importances** для каждой модели
3. Предсказание модели и сохранение сабмишена (скор на привате *0.86*)
