# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

16.12.2020 - 17.12.2020 было проведено тестирование установки и функциональное тестирование программы Credit Card Number Validator.

На тестирование затрачено: 2 часa

В результате тестирования выявлены следующие дефекты:
* [Не проходит валидация карт бренда American Express #1](https://github.com/GeorgKonst/Java-1.1-2/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Руководство по установке IntelliJ IDEA


В качестве тестовых данных использовались номера карт различных банков с сервиса [tools.seo-zona.ru](https://tools.seo-zona.ru/credit-card-generator.html)

* **VISA:**  4438478611825334,  4068517954893479,  4234558049773788
* **Discover:**  6011442203058399,  6011809757849821,  6011438157792546
* **American Express:**  346250582534438,  373719115484812,  379809784814128
* **Mastercard:** 5268897349817416,  5234120390817032,  5234120390817032
* **JCB:**  3529720474831236,  3579135110069142,  3558203939112405


Тестирование производилось в следующем окружении:
* Microsoft Windows [Version 10.0.19042.685] x64
* java version "11.0.9" 2020-10-20 LTS
* IntelliJ IDEA 2020.3 (Community Edition) Build #IC-203.5981.155, built on December 1, 2020
