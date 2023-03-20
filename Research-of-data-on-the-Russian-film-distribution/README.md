# Skills and libraries:

Pandas, NumPy, Matplotlib, correlation detection, plotting

# Project Description

The customer of this study is the Ministry of Culture of the Russian Federation.
You need to study the Russian film distribution market and identify current trends. Pay attention to the films that have received state support. Try to answer the question of how interesting such films are to the viewer.
You will work with the data published on the [open data portal of the Ministry of Culture](https://opendata.mkrf.ru/). The data set contains information about rental certificates, fees and state support for films, as well as information from the KinoPoisk website.

# The purpose of the study

It is necessary to study the Russian film distribution market and identify current trends. Pay attention to films that have received state support. Find out how interesting such films are to the viewer.

# Data description 

The mkrf_movies table contains information from the register of rental certificates. One film can have several rental certificates.

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

Note that the budget column already includes the full amount of government support. The data in this column is only for those films that have received state support.
The mkrf_shows table contains information about movie screenings in Russian cinemas.

- puNumber — number of the rental certificate;
- box_office — fees in rubles.

# General conclusion


For world cinema :

49,622,695,308.8 - Maximum fees

2,425,499.0 - Minimum fees

by fees, the most popular category is "16+"

The most profitable year would be 2017

For Russian cinema:

It is difficult to talk about trends specifically for films with state support, since the sample is only 300 films.

state support:

The largest number of films with state support is up to 100 million rubles.

The minimum support is 3 million, and the maximum is 500 million

Most often there is state support in the amount of 35 million
