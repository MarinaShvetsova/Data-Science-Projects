# Описание проекта - Рекомендация тарифа
## Данные

Каждый объект в представленных данных — это информация о поведении одного пользователя за месяц.
Описание данных:
— количество звонков
- суммарная длительность звонков в минутах
- количество sms-сообщений
- израсходованный интернет-трафик в Мб
- каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0)

## Задача

Построить модель для задачи классификации, которая выберет подходящий для пользователя тариф. 
Метрика качества модели - accuracy, должна быть не менее 0.75

## Используемые библиотеки
*pandas*,
*scikit-learn*