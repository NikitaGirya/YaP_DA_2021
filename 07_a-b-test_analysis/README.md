---

:white_check_mark::ok_hand:Для корректного отображения разметки `Markdown`, `LaTeX` и интерактивности графиков `Plotly` </br>
**[Cмотреть через Jupyter Notebook Viewer](https://nbviewer.org/github/NikitaGirya/a-b-test_analysis/blob/main/Girya_a-b-test_analysis.ipynb)**

---

# Анализ А/В-теста

`pandas`  `numpy`  `math`  `scipy`  `matplotlib`  `seaborn`  `plotly`

---

<p align='center'>
  <img src='https://cdn.pushalert.co/img/ab-testing-push-notifications.gif' width=650 height=300 />
</p>

---

Вместе с отделом маркетинга подготовлен список гипотез для увеличения выручки. Задача: приоритизировать гипотезы, запустить A/B-тест и проанализировать результаты

---

### Задачи исследования


**Часть 1.** Подготовка данных: получение и обзор, выявление видимых и скрытых аномалий

**Часть 2.** Приоритизация гипотез

В файле `hypothesis.csv` 9 гипотез по увеличению выручки интернет-магазина с указанными параметрами *Reach*, *Impact*, *Confidence*, *Effort*

* Применение фреймворка *ICE* для приоритизации гипотез. Сортировка их по убыванию приоритета
* Применение фреймворка *RICE* для приоритизации гипотез. Сортировка их по убыванию приоритета
* Определение измения приоритизации гипотез при применении *RICE* вместо *ICE*. Объяснение причин

**Часть 3.** Анализ A/B-теста

В результате проведенного A/B-теста получены результаты, описанные в файлах `orders.csv` и `visitors.csv`

1. *Проверка результатов теста на корректность*:

    * Периода проведения теста
    * Баланса пользователей в каждой группе
    * Принадлежности пользователя только одной группе </br>

2. *Визуализация результатов теста.* Построение и расчет:
    * Графика кумулятивной выручки по группам
    * Графика кумулятивного среднего чека по группам. 
    * Графика относительного изменения кумулятивного среднего чека группы B к группе A
    * Графика кумулятивной конверсии по группам
    * Графика относительного изменения кумулятивной конверсии группы B к группе A
    * Точечного графика количества заказов по пользователям
    * 95-го и 99-го перцентилей количества заказов на пользователя. Выбор границы для определения аномальных пользователей
    * Точечного графика стоимостей заказов
    * 95-го и 99-го перцентилей стоимости заказов. Выбор границы для определения аномальных заказов </br>

3. *Расчет статистической значимости различий в*:
    * конверсии между группами по «сырым» данным
    * среднем чеке заказа между группами по «сырым» данным
    * конверсии между группами по «очищенным» данным
    * среднем чеке заказа между группами по «очищенным» данным </br>

4. *Принятие решения по результатам теста*:
    * Остановка теста, фиксация победы одной из групп
    * Остановка теста, фиксация отсутствия различий между группами
    * Продолжение теста

---

:white_check_mark::ok_hand:Для корректного отображения разметки `Markdown`, `LaTeX` и интерактивности графиков `Plotly` </br>
**[Cмотреть через Jupyter Notebook Viewer](https://nbviewer.org/github/NikitaGirya/a-b-test_analysis/blob/main/Girya_a-b-test_analysis.ipynb)**

---