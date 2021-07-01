 Отчёт о тестировании Credit-Card-Number-Validator

## Краткое описание

19.06.21-было проведено Функциональное тестирование приложения Credit-Card-Number-Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не проверяет карты American Express (AMEX) разрядностью 15](https://github.com/Uzbek150885/Credit-Card-Number-Validator/issues/4)
* [Не проверяет карты Diners Club - Carte Blanche разрядностью 14](https://github.com/Uzbek150885/Credit-Card-Number-Validator/issues/3)
* [Не проверяет карты Обнаруживает разрядностью 19](https://github.com/Uzbek150885/Credit-Card-Number-Validator/issues/2)
* [Не проверяет карты VISA разрядностью 19](https://github.com/Uzbek150885/Credit-Card-Number-Validator/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные [с ресурса:](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* ОС Win 8.1, 64x
* версия Java: "11.0.11"
* [исходник проекта на GitHub](https://github.com/Uzbek150885/Credit-Card-Number-Validator/blob/master/src/Main.java)
