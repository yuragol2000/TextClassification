# Text Classification Project

## 📚 Описание
Этот проект посвящен задаче классификации текстов, целью которого является предсказание темы текста на основе заголовка и содержимого. В рамках проекта были реализованы различные модели машинного обучения, включая Logistic Regression, Naive Bayes, KNeighborsClassifier, CatBoost и Random Forest, с применением различных методов векторизации, таких как CountVectorizer, TfidfVectorizer, Word2Vec и Doc2Vec.

## ⚙️ Стек технологий
- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Keras (для нейронных сетей)
- Jupyter Notebook

## 🧩 Задачи
- Предобработка текстовых данных
- Обучение и оценка различных моделей классификации
- Сравнение производительности моделей с использованием метрик: accuracy, recall, precision и F1-меры

## 📊 Результаты
В ходе экспериментов были получены следующие результаты для различных моделей:
- **Logistic Regression с CountVectorizer**: 
- **CNN с Embedding**:
  
- **KNeighborsClassifier**: Значительно более низкие результаты, что указывает на необходимость выбора более подходящих алгоритмов для данной задачи.

| Модель                                     | Precision | Recall   | F1       | Accuracy |
|--------------------------------------------|-----------|----------|----------|----------|
| CountVectorizer с Logistic Regression      | 0.921698  | 0.926280 | 0.923930 | 0.930904 |
| CountVectorizer с MultinomialNB           | 0.910392  | 0.907233 | 0.908646 | 0.918686 |
| CountVectorizer с KNeighborsClassifier     | 0.311000  | 0.590372 | 0.293454 | 0.341016 |
| CountVectorizer с CatBoostClassifier       | 0.858586  | 0.887065 | 0.871172 | 0.881453 |
| RandomForest с CountVectorizer            | 0.846442  | 0.900962 | 0.864374 | 0.883304 |
| TfidfVectorizer с Logistic Regression      | 0.916782  | 0.925461 | 0.920917 | 0.928636 |
| TfidfVectorizer с MultinomialNB           | 0.894258  | 0.899487 | 0.896699 | 0.908365 |
| TfidfVectorizer с CatBoostClassifier      | 0.851952  | 0.882430 | 0.865263 | 0.876409 |
| TfidfVectorizer с RandomForestClassifier   | 0.832055  | 0.880865 | 0.848763 | 0.869120 |
| Word2Vec с Logistic Regression             | 0.896645  | 0.903934 | 0.900140 | 0.910818 |
| Word2Vec с KNeighborsClassifier            | 0.877129  | 0.893821 | 0.884128 | 0.898808 |
| Word2Vec с CatBoostClassifier              | 0.894686  | 0.901078 | 0.897699 | 0.909106 |
| Word2Vec с RandomForestClassifier          | 0.877395  | 0.894876 | 0.885135 | 0.899317 |
| Word2Vec+TfidfVectorizer с Logistic Regression | 0.878435  | 0.888138 | 0.882869 | 0.896703 |
| Word2Vec+TfidfVectorizer с CatBoostClassifier | 0.891445  | 0.896380 | 0.893757 | 0.905473 |
| Word2Vec+TfidfVectorizer с KNeighborsClassifier | 0.865666  | 0.880021 | 0.870943 | 0.888187 |
| Word2Vec+TfidfVectorizer с RandomForestClassifier | 0.878239  | 0.894160 | 0.885132 | 0.899456 |
| CNN с Embedding                            | 0.924311  | 0.924375 | 0.924269 | 0.931042 |
