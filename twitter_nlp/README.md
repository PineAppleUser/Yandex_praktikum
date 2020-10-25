# Данные:
- text - текст комментария
- toxic - бинарная классификация 0/1


# Задача:
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.Обучите модель классифицировать комментарии на позитивные и негативные. 

# Используемые библиотеки
- pandas
- numpy
- tqdm.notebook
- sklearn
  - train_test_split
  - cross_val_score
  - GridSearchCV
  - f1_score
  - LogisticRegression
  - TfidfVectorizer
- nltk
  - punkt
  - averaged_perceptron_tagger
  - wordnet
  - stopwords
-pywsd
  - lemmatize_sentence
- torch
- transformers
  - DistilBertModel
  - DistilBertTokenizer
  - distilbert-base-uncased
  - BertModel
  - BertTokenizer
  - bert-base-uncased
- re
- lightgbm 
  - LGBMClassifier
