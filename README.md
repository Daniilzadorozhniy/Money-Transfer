# Отчёт о тестировании приложения "Money Transfer"

### Был протестирован код функции пополнения баланса приложения "Money Transfer". В ходе тестирования был обраружен критический баг (Приложение "ломается" если сумарный лимит Балланса на счету клиента более чем 2147483647 рублей).

## Описание тестов

Проводилось тестирование методом белого ящика

Тестирование кода

Функциональное (позитивное)

* Пополнение счета положительным числом


## Результаты

Всего было проведено 10 тестов:

9 успешных/ 1 не успешный

Был обнаружен критический Баг

**Приложение "ломается" если сумарный лимит Балланса на счету клиента более чем 2147483647 рублей**


## Ссылка на баг-репорт

[Оператор int totalSum в приложении Money Transfer выполняется не корректно #1](https://github.com/Daniilzadorozhniy/Money-Transfer/issues/1)

## Общие рекомендации

?