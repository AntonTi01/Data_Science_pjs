
## Проект. Отток клиентов
### Описание проекта
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Нужно построить модель с предельно большим значением *F1*-меры. Нужно довести метрику минимум до 0.59.  
Проверить *F1*-меру на тестовой выборке.

Дополнительно измерить *AUC-ROC*, сравнивая её значение с *F1*-мерой.

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

### Содержание проекта
1 - Ознакомление с данными.  
2 - Исследование баланса классов, обучение модели без учёта дисбаланса.  
3 - Улучшение качества модели, учитывая дисбаланс классов. Обучение разных модели и нахожение лучшей.  
4 - Проверка качество модели на тестовой выборке.

### Библиотеки, используемые в проекте:
- Pandas
- Matplotlib
- SKlearn
- Numpy
- Seaborn
