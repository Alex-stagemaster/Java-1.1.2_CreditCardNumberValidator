# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
15.03.2021 - 15.03.2021 было проведено тестирование установки и функциональное тестирование программы Credit Card Number Validator.

На процесс тестирования было затрачено: 1,5 часa

В результате тестирования выявлены следующие дефекты:

1) [Не проходит валидация карт VISA с номером из 19-ти знаков](https://github.com/Alex-stagemaster/Java-1.1.2_CreditCardNumberValidator/issues/1) 
2) [Не проходит валидация карт Discover с номером из 19-ти знаков](https://github.com/Alex-stagemaster/Java-1.1.2_CreditCardNumberValidator/issues/2)
3) [Не проходит валидация карт American Express](https://github.com/Alex-stagemaster/Java-1.1.2_CreditCardNumberValidator/issues/3)
4) [Не проходит валидация карт JCB с номером из 19-ти знаков](https://github.com/Alex-stagemaster/Java-1.1.2_CreditCardNumberValidator/issues/4)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались номера карт различных банков с сервиса [www.freeformatter.com:](https://www.freeformatter.com/credit-card-number-generator-validator.html)

* VISA: 
4067818455422607,
4716609472359525,
4929393026816523183,

* Discover: 
6011334084091757,
6011197196902256,
6011086427131766811,

* American Express: 
377893535035797,
348342631741193,
344644627208010,
* Mastercard: 
5231736121757859,
5514888399696158,
5428689549702192,
* JCB: 
3544330270141607,
3529987285794412,
3537885883860236311,

Тестирование производилось в следующем окружении:

* Windows 7 Service Pack 1 x64
* Java version 11.0.10
* version 2.30.0.windows.2
