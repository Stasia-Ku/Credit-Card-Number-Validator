 ## Краткое описание ##

28.06 21.00 - 28.06 21.30 было проведено функциональное тестирование на валидность номера банковской карты.

На тестирование затрачено: 0,5 ч.

В результате тестирования выявлены следующие дефекты:

https://github.com/Stasia-Ku/javaqa-homework-1.2/issues/1 

https://github.com/Stasia-Ku/javaqa-homework-1.2/issues/2

## Описание процесса тестирования: ##

В процессе тестирования использовались следующие артефакты:

* баг-репорт
* отчет о тестировании

В качестве валидных тестовых данных использовались номера банковских карт https://www.freeformatter.com/credit-card-number-generator-validator.html

Валидные данные:
* VISA:

 4929221320237904
 
 4532846367806424
* MasterCard:

5343631646232683

5507006511472965
* Maestro:

6763049779986711

5020599328192303

* American Express (AMEX):

346797301046128

* Discover:

6011105661112578137

Ожидаемый результат: 

Номера карт пройдут тест на валидность, система покажет нам результат: Result is OK

Невалидные данные: 

5

6763049779986711676304977998671163049779986711998671163049779986711

676304977998671A

502059932819230!









Ожидаемый результат: 

Номера карт не пройдут тест на валидность, система покажет нам результат: Result is FAIL

Тестирование производилось в следующем окружении:

MacBook Pro

macOS 10.15.4

Java 11.0.7

IntelliJ IDEA
