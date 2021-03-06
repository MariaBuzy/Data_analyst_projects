# Изучение закономерностей, определяющих успешность игр
### Статус проекта: Завершен
На основе истоирческих данных о продажах компьютерных игр:
* пользовательская оценка,
* экспертная оценка,
* жанр,
* платформа,
* год выпуска  

нужно было выявить закономерности, определяющие, что игра успешная у пользователей.

## Что сделано
Найдены параметры, по которым можно определить, была ли успешна игра в разных регионах. Был подготовлен отчет и рекомендации для магазина компьютерных игр для планирования рекламных кампаний.  
В ходе проекта была проведена предобработка данных и их анализ:
* применены два подхода для анализа: по игровым консолям и по актуальному периоду,
* составлены портреты пользователей по регионам,
* проверены гипотезы:
  *  средние пользовательские рейтинги платформ Xbox One и PC одинаковые,
  *  средние пользовательские рейтинги жанров Action и Sports разные.
Был использован критерий Стьюдента для независмых выборок.

## Выводы по проекту
**Задача исследования:** Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

В ходе исследования выявленны закономерности: Самые успешные игры выпущены на английском языке для приставок PS3, X360 и PS4. Самый активный потребитель игр - это NA-регион и EU-регион. Самые популярные жанры в этих регионах: Action, Shooter, Sports.  
Игры в этих жанрах так же и выпускаются в большем количестве.  

Самые успешные жанры:

* Shooter - на 1 игру в среднем приходится 1.1 миллион продаж.  
* Platform - на 1 игру в среднем приходится 1 миллион продаж.  
* Sport - на 1 игру в среднем приходится 0,7 миллионов продаж.  
* Для Ja-ругиона нужно учитывать региональную специфику, так как они предпочитают игры в жанрах Role-playing, Action и Misc. Пользователи Ja-региона предпочитают портативные консоли, но сам рынок небольшой. Так же регион специфический, здесь много продаж игр без рейтинга, которые, скорее всего являются локальными, созданными под азиатский рынок. Реклама должна создаваться точечно и только на Ja-регион.

Не следует тратить деньги на рекламу игр для приставок, которые уже вышли из употребления.

В последние 5 лет наблюдается три направления продаж по рейтингу ESRB:

* покупается много игр с рейтингом 18+.
* нейтральные игры, которые походят для всех возрастов.
* игры без рейтинга (возможно, не предназначенные для рынка США).

### Рекомендации
При ограниченном бюджете:
Универсальным продуктом для всех регионов являются игры в жанре Action для приставок PS3.  
Наиболее привлекательный регион - NA, так как там самая большая аудитория.  
Так же следует провести дополнительное исследование конкурентов и удовлетворенности спроса в этом регионе.  



## Необходимые библиотеки
import pandas as pd  
import numpy as np  
from scipy import stats as st  
import matplotlib.pyplot as plt  
