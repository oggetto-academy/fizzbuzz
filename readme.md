# Небольшие задачи по программированию
## FizzBuzz
Напишите программу, которая выводит на экран числа от 1 до 100. При этом вместо чисел, кратных трем, программа должна выводить слово «Fizz», а вместо чисел, кратных пяти — слово «Buzz». Если число кратно и 3, и 5, то программа должна выводить слово «FizzBuzz»

## Проверка на палиндром
[Палиндром](https://ru.wikipedia.org/wiki/Палиндром) — набор символов (строка, число или предложение), одинаково читающийся в обоих направлениях. Например: «Аргентина манит негра», «43234», «топот» и т. д.

Напишите функцию, которая проверяет, является ли ее аргумент палиндромом. Функция принимает один аргумент: строку, число или предложение и возвращает булево значение.

Например:

```js
isPalindrome('test'); // false
isPalindrome('radar'); // true
isPalindrome('Аргентина манит негра'); // true
```

## Однозначная сумма цифр из числа
Напишите функцию, которая принимает число и суммирует цифры, из которых оно состоит, до тех пор, пока не останется однозначное число. Функция должна вернуть одну цифру.

Пример:

```js
sumDigits(42); // вернет 6: 4 + 2 = 6
sumDigits(84); // вернет 3: 8 + 4 = 12, 1 + 2 = 3
```

