# Четвертый проект. 

Основной задачей было предсказать выгодный тариф для клиента на основе базовых моделей машинного обучения: логистическая регрессия, решающее дерово или случайный лес.
Задача классификации.
В ходе выполнения проекта отработаны навыки исследования данных, зависимость целевого признака с признаками, на которых строится обучение. Определение важности признаков для предсказания.

# Данные
В наличии были следующие данные о клиентах компании:
- сalls — количество звонков,
- minutes — суммарная длительность звонков в минутах,
- messages — количество sms-сообщений,
- mb_used — израсходованный интернет-трафик в Мб,
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

# Описание проекта.
В нашем распоряжении данные абонентов мобильной связи.
Многие клиенты пользуются архивными тарифами. Поэтому стоит задача построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». 
В имещемся файле данные клиентов, которые уже перешли на эти тарифы.
Задача построить модель для задачи классификации, которая выберет подходящий тариф. Необходимо постройть модель с максимально большим значением accuracy.


Целевая доля правильных ответов должна быть более 0.75.


# Используемые библиотеки:
pandas, sklearn, matplotlib.pyplot, seaborn.
