# Выпускной проект на курсе "Аналитика данных" Karpov Courses
Цели:
1. Проанализировать результаты А/В теста для образовательной платформы;
2. Выгрузить из СУБД Clickhouse данные по результатам А/В теста для образовательной платформы и получить ключевые метрики по разным группам пользователей;
3. Автоматизировать загрузку дополнительных данных и построение графиков по метрикам из результатов А/В теста.<br>

Стек: Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib), SQL.<br>

Результаты:<br>
1. Проведён всесторонний статистический анализ результатов А/В теста с помощью Python, проанализированы ключевые метрики (ARPU, ARPPU, CR, медианный чек), принято решение не распространять изменение на всех пользователей, поскольку изменение метрик статистически не значимо;
2. Получены ключевые метрики (ARPU, ARPAU, CR) по разным группам пользователей;
3. Написаны функции на Python, позволяющие автоматически загружать дополнительные данные, пересчитывать ключевые метрики (ARPU, ARPPU, CR) по тестовой и контрольной группам и строить графики.
