## Билет 2

### Задача 1 (простая)
В магазине есть список покупок с количеством товаров:
```python
shopping_list = ["молоко", "хлеб", "яйца", "молоко", "масло", "хлеб", "молоко"]
```
Напишите программу, которая подсчитывает, сколько раз каждый товар встречается в списке, и выводит результат в виде словаря.

### Задача 2 (сложная)
Система учета зарплат сотрудников. Даны два словаря:
```python
employees = {
    "001": {"name": "Анна", "position": "менеджер", "hours": 160},
    "002": {"name": "Борис", "position": "программист", "hours": 180},
    "003": {"name": "Вера", "position": "дизайнер", "hours": 150}
}

hourly_rates = {
    "менеджер": 500,
    "программист": 800,
    "дизайнер": 600
}
```
Напишите программу, которая:
1. Рассчитывает зарплату каждого сотрудника
2. Находит сотрудника с максимальной зарплатой
3. Выводит общую сумму зарплат всех сотрудников