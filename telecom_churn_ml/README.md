# Данные:
- customerID - id клиента
- BeginDate - дата заключения
- EndDate - дата окончания
- Type - тип контракта
- PaperlessBilling - тип оплаты
- PaymentMethod - метод оплаты
- MonthlyCharges - месячное списание
- TotalCharges - всего списано
- InternetService - тип интернет подключения
- OnlineSecurity - онлайн безопасность
- OnlineBackup - онлайн резервная копия
- DeviceProtection - защита устройства
- TechSupport - техническая поддержка
- StreamingTV - Просмотр ТВ
- StreamingMovies - Просмотр кино
- gender - пол
- SeniorCitizen - пожилой(0/1) пользователь
- Partner - партнер(0/1)
- Dependents - зависимый финансово(0/1) пользователь
- MultipleLines - подключение к нескольким линям одновременно (0/1)

# Задача:
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов.

# Используемые библиотеки
- pandas
- matplotlib
- seaborn
- numpy
- sklearn
  - Shuffle
  - train_test_split
  - GridSearchCV
  - RandomForestClassifier
  - roc_auc_score
- catboost
  - CatBoostClassifier
  - cv
  - Pool 
  - get_feature_importance
