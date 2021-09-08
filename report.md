# Отчёт о тестировании Money transfer

## Краткое описание

08.09.2021 было проведено функциональное тестирование приложения Money transfer.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [неправильный подсчет данных](https://github.com/QA-NICK/QA-java-home-work-one/issues/1) 


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [тест кейс](https://docs.google.com/spreadsheets/d/1Ffty0P6WPlswRb_chsXI2VBWtG4_Zcfq6MGqIo_z4PU/edit?usp=sharing)

В качестве тестовых данных использовались данные, предоставленные из [домашнего задания](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md):
* currentBalance = 2_000_000_000
* transferSum = 500_000_000
* totalBalance = currentBalance + transferSum;

Тестирование производилось в следующем окружении:
* Windows 10 Enterprise LTSB x64
* openjdk version "11.0.11"
* IntelliJ IDEA Community Edition 2021.2.1