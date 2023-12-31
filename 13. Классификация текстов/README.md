# 13. Классификация текстов

### Цели проекта

- Обучить модель классифицировать комментарии по эмоциональному окрасу (позитивные, негативные). В распоряжении набор данных с разметкой о токсичности сообщений.
- Построить модель со значением метрики качества F1 не меньше 0.75.

### Задачи проекта

1. Предобработка Данных  
    - Лемматизация с помощью WordNetLemmatizer библиотеки nltk  
    - Удаление лишних символов  
    - Удаление стоп-слов (список взят из библиотеки nltk)  
    - Векторизация корпуса с помощью TfidfVectorizer  
2. Обучение моделей  
    - Logistic Regression  
    - CatBoost
    - Linear SVC  
3. Анализ результатов предсказаний

### Итоги

- На предобработанных данных (лемматизация -> очистка -> стоп-слова -> tf-idf) обучены модели: LogisticRegression, CatBoost, LinearSVC.
- Качество моделей практически одинаково. Разница не более 1%. Максимальный показатель **f1** получен для **NB-SVM: 0.783**  

### Используемый стек инструментов

- python
- pandas
- numpy
- sklearn
- nltk
- matplotlib
- seaborn
