# Анализ убытков приложения

## Задача проекта

Задача для маркетингового аналитика развлекательного приложения. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Моя задача — разобраться в причинах и помочь компании выйти в плюс.


| Название проекта | Описание | Используемые библиотеки |
| :--------------------: | :--------------------- |:---------------------------:|
| Анализ убытков приложения ProcrastinatePRO+| Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.| Python, Pandas, Matplotlib, когортный анализ, юнит-экономика, продуктовые метрики,Seaborn|

## План работы
### Предстоит изучить:

- откуда приходят пользователи и какими устройствами они пользуются,
- сколько стоит привлечение пользователей из различных рекламных каналов;
- сколько денег приносит каждый клиент,
- когда расходы на привлечение клиента окупаются,
- какие факторы мешают привлечению клиентов.

## Рекомендации для отдела маркетинга:

- Выяснить причину столь высоких затрат на рекламу в TipTop.
- Выяснить причины низкого удержания пользователей, пришедших через FaceBoom.
- Обратить внимание на PC пользователей, у которых низная конверсия при хорошем показании удержания.
- Также стоит обратить внимание на пользователей из европейских стран, где расходы на привлесчение стабильно окупаются.
- Рассмотреть возможность отказа от источник AdNonSense, так как он не достигает уровеня окупаемости, при при высокой стоимости привлечения.
- Стоит обратить внимание на канал Yrabbit - при низких затратах на рекламу, он показывает высокую и стабильную окупаемость. Но надо поработать над конверсией, этот показатель не растет и очень низкий.
- Также интересен канал RocketSuperAds - при уменьшении затрат, растет окупаемость.
