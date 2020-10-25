# Данные:
- RowNumber — индекс строки в данных
- CustomerId — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — количество недвижимости у клиента
- Balance — баланс на счёте
- NumOfProducts — количество продуктов банка, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая зарплата
- Exited — факт ухода клиента

# Задача:
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

# Используемые библиотеки
- pandas
- numpy
- sklearn
  - shuffle
  - train_test_split
  - StandardScaler
  - DecisionTreeClassifier
  - RandomForestClassifier
  - LogisticRegression
  - f1_score
  - roc_auc_score
  - recall_score
  - precision_score
