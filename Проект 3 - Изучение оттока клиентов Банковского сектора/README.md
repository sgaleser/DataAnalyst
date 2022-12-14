## Анализ оттока клиентов банка «Метанпром»

У нас есть данные о клиентах банка «Метанпром». Банк располагается в Ярославле и областных городах: Ростов Великий и Рыбинск.

Цели и Задачи

Необходимо проанализировать клиентов регионального банка и выделить портрет клиентов, которые склонны уходить из банка.
На основе исследования подготовить отчет в виде презентации, для принятия управленческих решений. [Презентация](https://disk.yandex.ru/i/UrbFAH04yrZRBw "Ссылка на презентацию")

В рамках финального проекта было необходимо построить дашборд в Tableau. [Ссылка на дашборд в Tableau](https://public.tableau.com/app/profile/aleksey6907/viz/ProjektBanksSergeevAS/Dashboard1?publish=yes "Дашборд финальный роект Сергеев Алексей") 
- Построить диаграмму, отражающую количество клиентов в зависимости от числа используемых продуктов.
- Добавить индикатор процента ушедших клиентов.
- Добавить фильтр дашборда по городу.


Использовано:
KMeans, Machine Learning, дендрограмма, RandomForestClassifier, LogisticRegression

Навыки которые использовались при решении проекта:

`Tableau` | `Python` | `Pandas` | `Scikit-learn` | `машинное обучение` | `классификация` | `кластеризация`|

Статуса проекта: `закончен`


**Вывод по проекту:**

- В Ростове Великом меньше всего клиентов и больше всего клиентов уходят в отток. Скорей всего в этом городе есть конкурент, который предлагает более интересные условия. Так-же возможно, в Ростове Великом плохое обслуживание клиентов или большие очереди, или долгое обслуживание стоит на это обратить внимание.
- Мы выяснили, что если клиент женщина, то веоятность, что она уйдет в отток 25 %. Мужчины уходят в отток 16 %. Скорей всего это тоже связано с условиями обслуживания, конкуренты предлагают более интересные условия. Бонусы и скидки. Можно предложить повышенный кэшбэк в магазинах косметики или за операции красота и уход.
- Клиенты берет кредит, выплачивает его и  уходит в отток. Стоит в период выплаты кредита предлагать дополнительные услуги.
