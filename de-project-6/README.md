# Поиск сообществ с высокой конверсией в первое сообщение

Описание: Создание аналитической базы данных, для помощи маркетологам решить задачу: разместить на сторонних сайтах рекламу сообществ с высокой активностью.

Стек: Python, Airflow, S3, SQL, PostgreSQL, Vertica

Выводы:
1. Перенесены из S3 в staging-слой новые данные о входе и выходе пользователей из групп.
2. Созданы таблицы для новых данных в слое постоянного хранения.
3. Перенесены новые данные из staging-области в слой DDS.
4. Рассчитаны конверсионные показатели для десяти самых старых сообществ.