---

:white_check_mark::ok_hand:Для корректного отображения разметки `Markdown`, `LaTeX` и интерактивности графиков `Plotly` </br>
**[Cмотреть через Jupyter Notebook Viewer](https://nbviewer.org/github/NikitaGirya/analysis_user_behavior/blob/main/Girya_analysis_user_behavior.ipynb)**

---

# Анализ поведения пользователей мобильного приложения

`pandas`  `numpy`  `math`  `scipy`  `plotly`

---

<p align='center'>
  <img src='https://www.affde.com/uploads/article/84322/kl5ULCEKzke6Yrd0.gif' width=700 height=350 />
</p>

---

Необходимо разобраться, как ведут себя пользователи мобильного приложения по продаже продуктов питания. Предстоит изучить воронку продаж – узнать, как пользователи доходят до покупки, сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно? После этого провести исследование результатов A/A/B-эксперимента, в котором пользователей разбили на три группы: две контрольные со старыми шрифтами и одну экспериментальную — с новыми. Выяснить, какой шрифт лучше

---

### Задачи исследования


**Этап 1.** Подготовка данных

* Получение и обзор данных
* Приведение названий столбцов к единому стилю
* Проверка пропусков и корректности типов данных
* Добавление столбца с датой и временем, а также отдельного столбца дат

**Этап 2.** Изучение и проверка данных

* Нахождение общего количества событий в логе
* Нахождение общего количества пользователей в логе
* Определение среднего количества событий на пользователя
* Определение актуального периода и фильтрация по нему
* Проверка присутствия пользователей из всех экспериментальных групп

**Этап 3.** Изучение воронки событий

* Сортировка событий в логах по частоте
* Сортировка событий в логах по числу уникальных пользователей
* Подсчет доли пользователей, которые хоть раз совершали событие
* Определение порядка событий
* Подсчет доли пользователей по шагам воронки 
* На каком шаге теряется больше всего пользователей? 
* Какая доля пользователей доходит от первого события до оплаты?

**Этап 4.** Изучение результатов эксперимента

* Определение количества пользователей в каждой экспериментальной группе
* Проверка статистической значимости A/A-эксперимента
* Проверка статистической значимости A/A/B-эксперимента
* Решение проблемы множественных сравнений при проверке статистических гипотез

**Этап 5.** Формирование общего вывода исследования

---

:white_check_mark::ok_hand:Для корректного отображения разметки `Markdown`, `LaTeX` и интерактивности графиков `Plotly` </br>
**[Cмотреть через Jupyter Notebook Viewer](https://nbviewer.org/github/NikitaGirya/analysis_user_behavior/blob/main/Girya_analysis_user_behavior.ipynb)**

---