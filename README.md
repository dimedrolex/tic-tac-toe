# Игра "Крестики-нолики"

===========================================================================

## Инструкция по использованию
Вводится три символа:
1й - целое число (от 1 до 3)
2й - пробел
3й - целое число (от 1 до 3)
Например: "1 2", "3 3", "3 2"

## Критерии выйгрыша:
Если "строка" или "столбец" или "диагональ" заняты одинаковым символом.

## Конец игры
- отсутсвие свободных клеточек с символом "."
- в случае выйгрыша:
    Если "строка" или "столбец" или "диагональ" заняты одинаковым символом.

===========================================================================

## Особенность проекта
Количество игроков: 2
Размер поля: 3x3
Нумерация клеток по вертикали (столбец): 1, 2, 3
Нумерация клеток по горизонтали (строка): 1, 2, 3
"." - означает что место не занято
"x" - у первого игрока крестик
"0" - у второго игрока нолик

field - игровое поле 3x3

Если cell = 1  Ход первого игрока с "x" // Выигрышь "первого игрока с "x"
Если cell = -1 Ход второго игрока с "0" // Выигрышь "второго игрока с "0" // Изначально
Если cell = 0  При заполнениии всех клеток // Ничья

=======================================================================================

use Python version 3.10