# Домашнее задание 1

## Дедлайн

8 октября 23:59 (UTC + 3).

## Часть 1

Реализовать логический элемент, вычисляющий медиану трех битов, с помощью полевых транзисторов.
Постарайтесь минимизировать количество использованных транзисторов.

Таблица истинностии для функции медианы (a, b, c - аргументы, r - результат):
| a | b | c | r |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

## Часть 2

Реализовать функции для конвертации целого числа в zig-zag encoding и обратно с помощью вашего любимого языка
программирования.

## Часть 3

Нарисовать функциональные схемы для любых двух из четырех логических элементов троичной логики (min, max, consensus, any).
Разрешается использовать все логические вентили для двух аргументов.

Трит кодируется с помощью двух бит:
* `-` - 00
* `0` - 01
* `+` - 10

Результирующая схема должна принимать 4 бита и возвращать 2 бита в соответствии с заданной таблицей истинности.
