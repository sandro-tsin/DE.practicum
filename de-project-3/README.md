# Обновление пайплайна обработки данных 

Описание: Обновление пайплайна обработки данных для интернет-магазина: добавление в витрину данных по отмене заказов и возврату средств, а также рассчет метрики по «возвращаемости клиентов».

Стек: Python, Airflow, S3, SQL, PostgreSQL, REST-API

Выводы:
1. Адаптирован пайплайн: в витрине учтены нужные статусы и обновлен пайплайн с учётом этих статусов. 
2. На основе пайплайна наполнена витрина данных по «возвращаемости клиентов» в разрезе недель. 
3. Перезапущен пайплайн и проведена проверка на наличие дубликатов в витринах.