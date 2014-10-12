Universal Rating Visualizer (UVR)
===

Авторы
------
Клевцов В. - руководитель/тех. райтер/кодер/тестер

Никитский Н. - кодер/архитектор/тестер

Пестун М. - тестер

Поцелуйко А. - кодер/верстальщик/тех. райтер

Цель
----
Дать подходящее визуальное отображение рейтинга студента, группы или факультета. Под подходящим визуальным отображением рейтинга понимается сопоставление среднему баллу студента, группы или факультета некоему изображению, отражающему успеваемость обучающейся единицы в интересующий нас промежуток времени (за первую контрольную неделю, за вторую контрольную неделю или за весь семестр).

Назначение
----------
Визуализация успеваемости студента, группы или факультета на основе данных рейтинга.

Область применения ПО
---------------------
Интернет-ресурсы, связанные с отображением рейтинга студентов ВолгГТУ (системы рейтинг-контроля студентов ВолгГТУ).

Аналоги
-------
| Свойство | Когнитивный визуализатор рейтинга  | Когнитивный ретинг "Лицо Чернова" | Универсальный визуализатор рейтинга |
|:--------:|:----------------------------------:|:---------------------------------:|:-----------------------------------:|
| Рейтинг студента | + | + | + |
| Рейтинг группы | + | - | + |
| Рейтинг факультета | - | - | + |
| Рейтинг ВУЗа | - | - | + |
| Многокритериальная зависимость | - | + | + |
| Гибкость системы к числу предметов | - | - | + |
| Контрольные срезы | + | + | + |
| Промежуточные срезы | - | - | - |
| Визуализация с градацией рейтинга | + | + | + |
| Наглядность визуализации | + | + | + |
| Изменение представлений | - | - | + |

Роли пользователей
------------------
1. Анонимный пользователь - незарегистрированный пользователь, который может только просматривать рейтинг.
2. Модератор - человек, вносящий данные об успеваемости студентов в систему (например, староста группы).
3. Администратор - человек, проверяющий работу модератора. Он может принять или отклонить введенные модератором данные. Также способен сам вносить нужные данные в систему (например, преподаватель).

Описание объекта проектирования
-------------------------------
Программа производит визуализацию данных системы рейтинг-контроля для выбранного студента, группы или факультета. Отображаемые данные состоят из рейтинга студента/группы/факультета по одному или нескольким предметам,  или успеваемости студента за всё время обучения.

Входные и выходные данные
-------------------------
Входные данные: успеваемость (рейтинг) студентов, взятые из базы данных.

Выходные данные: визуальное представление рейтинга студента, группы, факультета поодиночке или в сравнении.

Ограничение границ проекта
--------------------------
Визуализатор должен корректно работать с текущим количеством студентов, обучающихся в ВолгГТУ, а также с полным набором предметов, имеющихся в учебном плане.

Визуализатор должен работать с тремя группами предметов (профильные, дополнительные, смежные) и не более того.
Также программа должна уметь производить сравнение рейтингов следующих видов: “студент - студент”, “группа - группа” и “факультет - факультет” и никаких других. Сравнение рейтингов должно происходить между равнозначными обучающимися единицами.
