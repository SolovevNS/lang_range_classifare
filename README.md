NLP проект. Цель - создать ml решение для определения уровня сложности англоязычных фильмов для изучения английского языка. 
Всего 4 уровня: A2, B1, B2, C1. Предварительная разметка текста субтитров осуществялалась вручную с использованием Оксфордских словарей.
В проекте используется кастомная функция для очистки текста субтитров с использованием регулярных выражений, удалением лишних символов, 
токенизацией и лематизацией. Подбор гиперпараметров Optuna. Модели MultinominalNB и SVM.
Метрики accuracy и F1.
