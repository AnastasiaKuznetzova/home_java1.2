**Отчёт о тестировании Credit Card Number Validator**

Краткое описание

18 Ноября 2020 было проведено тестирование эквивалентных значений  Credit Card Number Validator.

На тестирование затрачено: 40 минут.

В результате тестирования выявлены следующие  дефекты:
- [Ограничение по длине номера кредитной карты.](https://github.com/AnastasiaKuznetzova/home_java1.2/issues/1)
- [Нельзя расплатиться картой American Express (AMEX)](https://github.com/AnastasiaKuznetzova/home_java1.2/issues/2)

- [Нельзя расплатиться картой платежной системы Diners Club - Carte Blanche/Diners Club - International](https://github.com/AnastasiaKuznetzova/home_java1.2/issues/3)

В качестве тестовых данных использовались данные :

- Номера кредитных карты с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)-есть дефекты( указаны выше)
- ввод пробела- система выдает FAIL
- отправка пустой строки- система выдает FAIL
- ввод букв -система выдает FAIL
- ввод символов-система выдает FAIL

Тестирование производилось в следующем окружении:

- ПК Windows 10
- Java version 11