# Классификация текстов с использованием TF-IDF для интернет-магазина «Викишоп»

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

Постройте модель со значением метрики качества *F1* не меньше 0.75.

## Задачи исследования
* провести загрузку и подготовку данных
* обучить несколько разных моделей
* сделать общий вывод, дать рекомендации

## Цели исследования
построить модель, которая сможет классифицировать комментарии на позитивные и негативные  
(критерий: *F1* >= 0.75)

## Данные для анализа
находятся в файле *toxic_comments.csv*

## Этапы работы над проектом

*Шаг 1.* Загрузка данных

* загрузка данных
* изучение общей информации
* анализ длины комментария

*Шаг 2.* Подготовка данных

* удаление неинформативных признаков
* оптимизация типов данных
* очистка текста + лемматизация
* мешок слов по классам

*Шаг 3.* Обучение

* подготовка данных
* обучение моделей
* тестирование лучшей модели

*Шаг 4.* Общий вывод  
