## Задание: Комментированная программа на C#

Создание консольное приложение на C#, которое демонстрирует все форматы Markdown в комментариях к коду.
#### Требования к программе:
1. **Имя файла:** `FormatDemo.cs`
3. **Логика:**
    - Заправивает у пользователя **два чиса**
    - Выполняет **их сложение**
    - Выводит результат в **форматированом виде**
---
#### Пример структуры кода с комментариями в стиле Marksown:
```cs
        Console.WriteLine("Введите первое число: ");
        double number1 = Convert.ToDouble(Console.ReadLine());
        Console.WriteLine("Введите второе число: ");
        double number2 = Convert.ToDouble(Console.ReadLine());
        double sum = number1 + number2;
        Console.WriteLine($"Результат операции: {sum}");
```