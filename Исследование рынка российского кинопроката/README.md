# Навыки и библиотеки:

Pandas, NumPy, Matplotlib, correlation detection, plotting

# Описание проекта

Изучить рынок российского кинопроката и выявить текущие тренды. Сделать аналих насколько  фильмы, которые получили государственную поддержку, интересны зрителю.
Источник [портал открытых данных Министерства культуры](https://opendata.mkrf.ru/). 

# Цель исследования

Выполнить исследование рынка российского кинопроката

# Data description 

Таблица mkrf_movies содержит информацию из реестра прокатных удостоверений. У одного фильма может быть несколько прокатных удостоверений.

- title — the name of the film;
- puNumber — the number of the rental certificate;
- show_start_date — movie premiere date;
- type — type of movie;
- film_studio — studio-producer;
- production_country — country of origin;
- director — director;
- producer — producer;
- age_restriction — age category;
- refundable_support — the amount of refundable state support funds;
- nonrefundable_support — the amount of non-refundable state support funds;
- financing_source — a source of government funding;
- budget — the total budget of the film;
- ratings — rating of the film on KINOPOISK;
- genres — the genre of the film.

- title — название фильма;
- puNumber — номер свидетельства об аренде;
- show_start_date — дата премьеры фильма;
- type — тип фильма;
- film_studio — студия-продюсер;
- production_country — страна происхождения;
- director — постановщик;
- producer — продюссер;
- age_restriction — возрастная категория;
- refundable_support — сумма подлежащих возврату средств государственной поддержки;
- nonrefundable_support — сумма невозвращаемых средств государственной поддержки;
- financing_source — источник государственного финансирования;
- budget — общий бюджет фильма;
- ratings — рейтинг фильма на КИНОПОИСКЕ;
- genres — жанр фильма.

Обратите внимание, что в графе "бюджет" уже указана полная сумма государственной поддержки. Данные в этой колонке относятся только к тем фильмам, которые получили государственную поддержку.
Таблица mkrf_shows содержит информацию о показах фильмов в российских кинотеатрах.

- puNumber — номер свидетельства об аренде;
- box_office — сборы в рублях.

# Вывод


Для мирового кинематографа :

49,622,695,308.8 - Максимальные сборы

2,425,499.0 - Минимальные сборы

по сборам самая популярная категория - "16+"

Самым прибыльным годом был бы 2017-й

Для российского кино:

Сложно говорить о тенденциях конкретно для фильмов с государственной поддержкой, поскольку выборка составляет всего 300 фильмов.

государственная поддержка:

Наибольшее количество фильмов с государственной поддержкой - до 100 миллионов рублей.

Минимальная поддержка составляет 3 миллиона, а максимальная - 500 миллионов

Чаще всего речь идет о государственной поддержке в размере 35 миллионов долларов
