# Решатель квадратных уравнений

**Код возвращает корни квадратного уравнения**

# Как использовать

Для использования get_roots необходимо импортировать его из quadratic_equation и задать значения аргументам a, b, c.

**Например:**
```python 
#импорт модуля
*from quadratic_equation import get_root*

#задается переменная с использованием фукнции, аргументы функции.
x = get_roots(1,2,-3)
print(x)

#результат кода
(-3.0, 1.0)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
