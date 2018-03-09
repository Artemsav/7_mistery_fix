# Quadratic Equations Solver (Описание проекта)

Function get_roots(a, b, c) return tuple with roots of quadratic equation, if there is no valid roots function returns: None, None.
Функция get_roots(a, b, c) возвращает кортеж с корнями квадратного уравнения, если нет корней функция возвращает: None, None. 

# How to use (Как использовать)

root1, root2 = get_roots(a, b, c)
Для получения корней уравнения задаешь коэфициенты a, b, c необходимо например задать get_roots(1, 3, 4) и вам выдаст кортеж с 
решением


How to Launch Tests (Как запустить тест):
python tests.py

in case of success output is the following: 
В случае успешного завершения теста вы получите:

python tests.py
....
----------------------------------------------------------------------
Ran 4 tests in 0.001s

OK



# Project Goals (Цели проекта)

Создания скрипта решения квадратного уравнения в паре со скриптом для тестирования уравнения с реализацией всех 
кейсво(дискриминант больше нуля, равен нулю, меньше нуля)