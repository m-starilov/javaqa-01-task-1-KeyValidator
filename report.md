# Отчёт о тестировании инструкции по установке OpenJDK11 для Windows и java приложения KeyValidator

## Краткое описание

20.11.2020 - 21.11.2020 было проведено функциональное тестирование java приложения KeyValidator, нефункциональное тестирвание инструкции по установке OpenJDK11

На тестирование затрачено: ~2 часа

В результате тестирования выявлены следующие дефекты:
1. [Приложение не работает согласно руководству использования](https://github.com/m-starilov/javaqa-01-task-1-KeyValidator/issues/1)
1. [Валидный ключ не проходит проверку](https://github.com/m-starilov/javaqa-01-task-1-KeyValidator/issues/2)
1. [Не валидный ключ проходит проверку](https://github.com/m-starilov/javaqa-01-task-1-KeyValidator/issues/3)

## Описание процесса тестирования

Для тестирования инструкции для ОС Windows были последовательно выполнены все шаги по инструкции. Все этапы выполняются корректно, рекомендую только добавить в шаги №4 и №5 указание "и нажмите кнопку "Next", чтобы исключить нажатие других кнопок пользователем. 

Приложение KeyValidator запускается и совместимо с Java 11.

Но приложение не работает согласно руководству использования. Ошибки приложения описаны в дефектах выше.


В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руковство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* Файл с исполняемым кодом [KeyValidator.class](https://github.com/m-starilov/javaqa-01-task-1-KeyValidator/blob/master/KeyValidator.class)

В качестве тестовых данных использовались данные:
* ключи для проверки из [руковства использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Тестирование производилось в следующем окружении:
*  ОС WIndows 10 Pro 64bit
*  OpenJDK11