# Contest

## Easy

+ Создать список, содержащий числа подряд от `1` до `100`
+ Выведите текущую дату и время в формате `"28.11.19 12:40"`
+ Превратите строку вида `"3, 5, 7, 23"` в массив целых чисел: `[3, 5, 7, 23]`
+ Дано число `n`, найдите значение выражения `n + nn + nnn` (например `n = 23`, тогда выражение будет: `23 + 2323 + 232323 == 234669`)
+ Посчитайте количество дней можду двумя датами (например, между `21.11.2019` и `28.11.2019`
+ Найдите день недели произвольной даты
+ Переведите все символы строки в нижний регистр (`"HeLLo"` -> `"hello"`)
+ Есть произвольная строка (например, `"abc"`), сделайте строку, содержащую три таких строки (`"abcabcabc"`)
+ Проверьте число на чётность и выведите `"odd"` или `"even"`
+ Проверьте, содержится ли число в массиве (`-1`, `3` в `[1, 5, 8, 3]`)
+ Найдите наибольший общий делитель двух положительных целых чисел (например, `48` и `18`) и их наименьшее общее кратное
+ У нас есть строка `"the quick brown fox jumps over a lazy dog"`:
  + Подсчитать количество всех символов в строке.
  + Подсчитать количество символов `a` в строке.
  + Подсчитать количество различных символов в строке.
  + Подсчитать количество слов в строке.
  + Создать список, содержащий все слова из строки.

## Medium

+ Напишите функцию, которая принимает два аргумента и возвращает:
  + Если оба аргумента целые числа - их сумму
  + Если оба аргумента списки:
    + Одинаковой длины - новый список, содержащий суммы элементов этих двух списков
    + Разной длины - бросает исключение `ValueError`
  + Если один аргумент список, а другой - целое число - список, содержащий суммы элементов исходного списка с этим числом