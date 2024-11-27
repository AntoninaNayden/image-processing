Сравнение алгоритмов

1. Пошаговый алгоритм
   
Преимущества:
Позволяет визуализировать процесс растеризации отрезка.
Является понятным для обучения и отладки.

Недостатки:
Неэффективен для больших отрезков из-за большого числа шагов.

2. Алгоритм ЦДА для отрезков
   
Преимущества:
Обеспечивает плавное изменение интенсивности цвета на отрезке.
Математически точен.

Недостатки:
Может требовать значительных вычислительных ресурсов.

3. Алгоритм Брезенхема для отрезков
   
Преимущества:
Легок в реализации.
Эффективен для пошагового рисования отрезков.

Недостатки:
Может приводить к накоплению ошибок, особенно на больших расстояниях.

4. Алгоритм Брезенхема для окружности
   
Преимущества:
Эффективен для рисования окружностей.
Прост в реализации.

Недостатки:
Может потребовать оптимизации при работе с большими окружностями.

Результаты тестов:

Пошаговый алгоритм: 413 мс

Алгоритм ЦДА: 430 мс

Алгоритм Брезенхема (отрезки): 354 мс

Алгоритм Брезенхема (окружности): 1698мс
