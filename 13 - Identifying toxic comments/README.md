# Natural Language Processing (NLP): Определение ''токсичных'' комментариев

[HTML](https://clck.ru/33QBcS)     [ipynb](https://clck.ru/33QBfr)

## Описание проекта

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

**Дано:**
Набор данных (комментарии пользователей к товарам в интеренет-магазине) с разметкой о токсичности: столбец `text` в нём содержит текст комментария, а `toxic` — целевой признак.

**Требуется:**
Модель для классифицирования комментариев на позитивные и негативные со значением метрики качества `F1` не меньше `0.75`

## Инструменты

- **python**
- **pandas**
- **nltk**
- **tqdm**
- **pymystem3**
- nltk.corpus.**StopWords**
- sklearn.feature_extraction.text.**TfidVectorizer**
- sklearn.model_selection.**train_test_split**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.ensemble.**GradientBoostingClassifier**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**f1_score**

## 

## Общий вывод

Из рассмотренных моделей наилучшие результаты показывает самая простая модель - модель `Логистической регрессии`
