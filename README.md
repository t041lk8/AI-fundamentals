# Лабораторные работы ФКИИ

Лабораторные работы по предмету "Фундаментальные концепции искусственного интеллекта" IT-магирстратуры МАИ

---

1. Градиентный спуск и его модификации
   - Выбрать [тестовые функции оптимизации](https://ru.wikipedia.org/wiki/Тестовые_функции_для_оптимизации) (2 шт)
   - Запрограммировать собственнуб реализацию классического градиентного спуска
   - Запрограммировать пайлайн тестирования алгоритма оптимизации
     - Визуализации функции и точки оптимума
     - Вычисление погрешности найденного решения в сравнение с аналитическим для нескольких запусков
     - Визуализации точки найденного решения (можно добавить анимацию на плюс балл)
   - Запрограммировать метод вычисления градиента
     - Передача функции градиента от пользователя
     - Символьное вычисление градиента (например с помощью [sympy](https://www.sympy.org/en/index.html)) (на доп балл)
     - Численная аппроксимация градиента (на доп балл)
   - Запрограммировать одну моментную модификацию и протестировать ее
   - Запрограммировать одну адаптивную модификацию и протестировать ее
   - Запрограммировать метод эфолюции темпа обучения и/или метод выбора начального приближения и протестировать их
   - `Will be unclocked afetr Lecture №5`
  2. Глобальная оптимизация и метаэврестические алгоритмы
     1. В Pygmo запрогроммировать две своих тестовых функции и найти их оптимум 3 разными алгоритмами доступными в библиотеке и получить таблицу сравнения
  3. Оптимизация гиперпараметров 
     1. С помощью [optuna]() взять пример, аналогичный третьему туториалу документации, используя sklearn и с другим датасетом, выбрать другие  алгоритмы классификации и клстеризации не из туториала  и визуализировать графики для полученного процесса
        1. В качестве других моделей подойдут любые алгоритмы классификации и регрессии из sklearn которые не использовались в туториале
     2. Использовать 2 разных семплера и прунера
     3. При процессе оптимизации гиперпараметров использовать общую память через postgreSQL
     4. В качестве отчёта выступают: исходный код, инструкция запуска реляционной БД. 
  4. Восстановление функции распренделения вероятности
     1. Реализовать метод восстановления плотности вероятности двумя способами:
        1. EM-алгоритм
        2. Ядерное сглаживание
     2. Применить данные методы на любом наборе случайных точек
   5. Реализовать метод Метрополиса-Гастингса и Гибсона для несимметричного распределения. Применить два метода на основе той функции плотности, которая была восстановлена в прошлом пункте, тем самым получив изначальные точки.
     4. в методе М-Г нарисовать картинку блуждания в случае 3D-функции плотности (на доп баллы)

---

# Курсовая работа

Исследование датасета
1. Краткое описание - что за датасет, откуда, для чего, можно с примером картинки или пример куска данных, не просто экземпляр данных, а показать даталоадер - класс или конструкция, которая для конкретного датасета предоставляет апи для доступа к данным
2. Статистика, нужно показать статистику по данным, количество полей, классов, объем данных, количество фичей, процент разбиения на классы, количество пропусков, типы данных
3. Алгоритм - на одном и том же датасете можно решать разные задачи, мы выбираем задачу конкретную и из бенчмарка. Мы приводим пример алгоритма машинного обучения, который на этом датасете может обучиться. Инференс.
4. Кластеризация/понижение размерности
5. Outlayers
6. ML-systems design