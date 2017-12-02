﻿# Решатель квадратных уравнений

Программа для нахождения корней квадратного уравнения.
Квадратное уравнение имеет вид ax2 + bx + c = 0. При его решении сначала вычисляют дискриминант по формуле D = b2 - 4ac. Если D > 0, то квадратное уравнение имеет два корня; если D = 0, то 1 корень; и если D < 0, то делают вывод, что корней нет.

# Как использовать
Одна функция get_roots получает три аргумента a, b, c
возвращает всегда два значения: либо два корня, либо один корень и None либо None и None

Импорт функции from quadratic_equation import get_roots

Пример вызова функции get_roots(1, -2, 1)

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
