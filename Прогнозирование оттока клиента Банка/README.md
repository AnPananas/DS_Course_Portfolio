
# Навяки и библиотеки:

Pandas, sklearn, matplotlib

# Описание проекта

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Источник данных: (https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

# Цель исследования

На основе данных из банка определить клиент, который может уйти

# Описание данных

Признаки
- RowNumber — индекс строки в данных
- CustomerID — уникальный идентификатор клиента
- Surname — фамилия
- CreditScore — кредитный рейтинг
- Geography — страна проживания
- Gender — пол
- Age — возраст
- Tenure — сколько лет человек является клиентом банка
- Balance — остаток на счете
- NumOfProducts — количество банковских продуктов, используемых клиентом
- HasCrCard — наличие кредитной карты
- IsActiveMember — активность клиента
- EstimatedSalary — предполагаемая заработная плата

Целевой признак
- Exited — факт ухода клиента
- 
# Вывод


В ходе исследования были подготовлены данные и протестированы три модели: Логистическая регрессия, Случайный лес и Дерево решений. Исследования проводились на несбалансированных и сбалансированных образцах, затем была выбрана наилучшая модель, на которой было проведено контрольное тестирование. Кроме того, была введена метрика auc_roc, которая показывает соотношение полноты и точности модели.

Наилучший показатель после балансировки классов показала модель случайного леса со значением F1-меры = 0,6, значением AUC-ROC =0,74

F1 - показатель больше 0,59 - задача выполнена.
