## Билет 10

### Задача 1 (простая)
Дан список чисел:
```python
numbers = [12, 45, 33, 78, 21, 56, 89, 34, 67, 23]
```
Напишите программу, которая:
1. Разделяет числа на четные и нечетные
2. Находит сумму четных и нечетных чисел отдельно
3. Определяет, каких чисел больше - четных или нечетных

### Задача 2 (сложная)
Банк ведет учет счетов клиентов:
```python
accounts = {
    "12345": {"name": "Анна Иванова", "balance": 50000, "type": "дебетовый"},
    "12346": {"name": "Борис Петров", "balance": 75000, "type": "кредитный"},
    "12347": {"name": "Вера Сидорова", "balance": 120000, "type": "дебетовый"}
}

transactions = [
    {"account": "12345", "amount": -5000, "type": "снятие"},
    {"account": "12346", "amount": 10000, "type": "пополнение"},
    {"account": "12345", "amount": 15000, "type": "пополнение"},
    {"account": "12347", "amount": -8000, "type": "снятие"}
]
```
Создайте программу, которая:
1. Обрабатывает все транзакции (обновляет балансы счетов)
2. Находит клиента с наибольшим балансом
3. Подсчитывает общую сумму средств на всех дебетовых счетах