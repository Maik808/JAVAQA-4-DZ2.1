﻿# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание

При вводе в приложение заданных значений программа вывела неверный результат. Проверка кода показала, что переменная total имеет неправильный тип данных.
Итоговое количество символов переменной total превысило допустимое значение для типа данных int. Также при используемом типе переменных невозможно отобразить дробную часть, т. е. копейки.

## Описание тестов

Проводилось позитивное функциональное тестирование. Проводилось тестирование модуля программы Money Transfer, ответственного за отображение баланса счета клиента после пополнения.


## Результаты

1.При присвоении переменной total значения, соответствующего типу данных int, программа возвращает корректный результат. В противном случае - возвращается      результат с ошибкой. Суммы с дробной частью (с копейками) невозможно ввести в переменные с типом int.

2.https://github.com/Maik808/JAVAQA-4-DZ2.1/issues/1#issue-575209436



## Общие рекомендации

Необходимо задать переменным balance, transfer_amount, total тип double





