# Десятый проект 

Обработка текстов.

Задача по классифицикации комментариев на позитивные и негативные

В ходе выполнения проекта отработаны навыки:
- загрузка и исследование данных;  
- проверка на диссбаланс классов;  
- обработку текста:  
       - очистка текста;  
       - лемматизация (используя SPACY);  
- работа с методом TfidfVectorizer для кодирования слов в велечины TF-IDF;     
- подбор гиперпараметров используя метод GridSearchCV;
- работа с моделью Логистическая регрессия, SVM и lightgbm.
- определение "лучшей" модели по скорости обучения и предказания.


# Данные
В наличии были следующие данные комментариях клиентов:
text - текст комментария, 
toxic — целевой признак.


# Описание проекта.

В нашем распоржении данные интернет магазина "Викишоп", которые содержат описание товаров. Пользователи могут дополнять и редактивровать описания товаров, а также комментировать описания других пользователей.

Нам необходимо построить модель, которая будет определять токсичность комментария и отправлять его на модерацию.

Цель задачи: разработать модель, которая покажет значение метрики качества F1 не менее 0.75

# Используемые библиотеки:

pandas, seaborn, matplotlib.pyplot, numpy, sklearn, catboost, lightgbm, nltk, time, re, spacy
