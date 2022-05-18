Запускаем тесты, видим, что они прошли успешно
![img](screens/Screenshot_8.png)

Допустим ошибку в скрипте, чтобы увидеть, что тест выдаст ошибку

![img](screens/Screenshot_9.png)

![img](screens/Screenshot_10.png)

Теперь запустим сервер, чтобы провести новое тестирование

![img](screens/Screenshot_6.png)

Запускаем тест

![img](screens/Screenshot_11.png)

Теперь сделаем ошибку, чтобы завалить тест

![img](screens/Screenshot_12.png)

Вернули всё на этап, когда не было ошибок.

## Работа с Azure

Создал проект для веб-приложения

![img](screens/Screenshot_1.png)

Проверим его работоспособность и убедимся, что всё хорошо

![img](screens/Screenshot_2.png)

![img](screens/Screenshot_3.png)

Подключим к Azure свой репозиторий 

![img](screens/Screenshot_13.png)

Переходим в пайплайн. Выполним все stages
![img](screens/Screenshot_15.png)
Видим, что опубликован артефакт.
![img](screens/Screenshot_16.png)

![img](screens/Screenshot_17.png)

Создаем release в Pipeline. Проводим настройку

![img](screens/Screenshot_18.png)

![img](screens/Screenshot_20.png)

Проводим тесты и видим, что тесты прошли успешно

![img](screens/Screenshot_22.png)

Переходим на сайт и видим, что он работает

![img](screens/Screenshot_23.png)

Теперь настраиваем функциональное тестирование. Добавим еще один stage и настроим его

![img](screens/Screenshot_24.png)

![img](screens/Screenshot_25.png)

Запускаем тесты и видим, что всё выполнилось

![img](screens/Screenshot_26.png)

Смотрим результаты

![img](screens/Screenshot_27.png)


