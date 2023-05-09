# Анализ соц. сетей

Проект созданный [dikiydinozavrik](https://github.com/dikiydinozavrik) и [ForwardMoth](https://github.com/ForwardMoth)

## [Лабораторная работа 1 "Сбор данных и анализ групп пользователей социальной сети ВКонтакте"](https://github.com/ForwardMoth/network_analysis/blob/main/lab1/lab1.ipynb)

- Выбраны 2 сообщества в социальной сети ВКонтакте
- Сохранение списка участников и их сравнение
- Сравнение хэштегов под постами в обоих сообществах и визуализация распределения хэштегов
- Анализ активности постов в сообществах
- Построение социального графа
- Кластеризация пользователей внутри сообществ 

## [Лабораторная работа 2 "Исследование социального графа, расчёт его характеристик"](https://github.com/ForwardMoth/network_analysis/blob/main/lab2/lab2.ipynb)

Использован граф, полученный в ЛР 1. 

- Поиск авторитетных пользователей с помощью метрики "Центральность". 

  **Центральность** - число минимальных кратчайших путей между любыми двумя его “друзьями” или “собеседниками”, проходящих через него.
- Вычисление плотности графа. 

  **Плотность графа** - это отношение реального числа связей в графе к максимально возможному в неориентированном графе с тем же числом вершин.
- Определение связности графа.  

  **Связность графа** - граф, содержащий ровно одну компоненту связности. Это означает, что между любой парой вершин этого графа существует как минимум один путь.
- Расчёт максимального, минимального и среднего значения степени узлов графа.
- Расчёт модулярности графа.

  **Модулярность** - это скалярная величина из отрезка [−1, 1], которая количественно описывает неформальное определение структуры сообществ
  
  
## [Лабораторная работа 3 "Анализ эмоциональной окраски пользовательских постов"](https://github.com/ForwardMoth/network_analysis/blob/main/lab3/lab3.ipynb)
- Была выполнена преобработка датасетов covid_19_tweets и Covid 19 Indian Sentiments
- Последний датасет был использован для обучения двух классификатор для предсказания метки класс: sad или joy
- Из двух использовавшихся классификаторов (Naive Bayes Classifier и K Neighbors Classifier)для дальнешей работы был выбран Naive Bayes Classifier как более точный
- Далее было предсказано настроение для твитов из датасета covid_19_tweets
- Рассчитана и визуализирована доля твитов, относящихся к классу sad
- С помощью библиотеки TextBlob была произведена оценка настроения (Neutral, Negative, Positive)
- Рассчитана и визуализирована доля твитов, относящихся к классам Neutral, Negative, Positive

## Лабораторная работа 4  (В процессе разработки)

## [Лабораторная работа 5 "Построение моделей сообществ"](https://github.com/ForwardMoth/network_analysis/blob/main/lab5/lab5.ipynb)

 Для выполнения лабораторной работы были использованы сообщества из Лабораторной работы 1 и построены два социальных графа для каждого сообщества

- Построение функции распределение степеней узлов для обоих сообществ
- Вычисление кластерных коэффициентов обоих сообществ
- Вычисление средней длины пути обоих графов
- Сопоставление моделей графа с существующими моделями (Random, BA, WS)
