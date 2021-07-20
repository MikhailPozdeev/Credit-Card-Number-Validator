# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

12.07.2021 - 12.07.2021 было проведено Функциональное тестирование приложения Credit Card Number Validator

На тестирование затрачено: 3.5 часа.

В результате тестирования выявлены следующие дефекты:
* [Issue] (https://github.com/MikhailPozdeev/Credit-Card-Number-Validator/issues)

## Описание процесса тестирования

В качестве тестовых данных использовались данные:
* [Credit Card Number Generator & Validator](www.freeformatter.com/credit-card-number-generator-validator.html)

## VISA - 4929830531431476 Result is OK
## VISA - 4556551848991727 Result is OK
## VISA - 4532042419921947867 Result is FAIL
## Discover - 6011233064361349 Result is OK
## Discover - 6011617182598802348 Result is FAIL
## American Express (AMEX) - 375384250284960 Result is FAIL
## American Express (AMEX) - 340224594486354 Result is FAIL

Тестирование производилось в следующем окружении:
* Windows 10  версия 20H2
* Java "11.0.11"
* IntelliJ IDEA Community Edition
