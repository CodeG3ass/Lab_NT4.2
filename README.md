# Lab_NT4.2
Балансировка нагрузки и сертификаты SSL 
Балансировка нагрузки и сертификаты SSL 

Цель работы 

Получить навыки продвинутой настройки сложного взаимодействия сетевых служб и сервисов в ОС Linux. 

Задания для выполнения 

Работа производится на виртуальной машине с установленным в ходе предыдущих работ сервером Apache и настроенными виртуальными хостами. 

Установить в виртуальной машине сервер Nginx. 

Настроить сервера Apache и Nginx так, чтобы 8080 порт Apache получал запросы 80 порта Nginx. 

Проверяем A1.com, Nginx accessA1.log должен пополняться при обращении к сайту. 

Проверяем B1.com, Nginx accessB1.log должен пополняться при обращении к сайту. 

Проверяем C1.com, Nginx accessC1.log должен пополняться при обращении к сайту. 

Log файлы должны быть разные для каждого сайта 

Делаем, чтобы Nginx всё, кроме jpg и png файлов передавал Apache. 

Склонировать виртуальную машину и запустить второй экземпляр. Настроить сетевой взаимодействие между машинами и хостом. 

 

Настройка SSL сертификатов 

Создать самоподписанный сертификат для сайтов A1.com, B1.com, C1.com 

Организовать работу Apache с по протоколу HTTPS (SSL) 

Перенаправление HTTP в HTTPS для Apache 

 

Дополнительные задания: 

 

Просмотреть содержимое сертификата 

Просмотреть содержимое сертификата в режиме обычного текста 

Проверить действительно ли сертификат подписан нужным CA 

Перевести Nginx на работу  с использование самоподписанного сертификата SSL 

Настроить отправку файлов проекта и конфигурации на GitHub 

![image](https://user-images.githubusercontent.com/92590831/145730644-365bc692-ecab-4d5c-9ca4-8ed047d7f5d3.png)

![image](https://user-images.githubusercontent.com/92590831/145730659-0dbca7c7-b519-4750-9b9b-15cef17d0e0c.png)

![image](https://user-images.githubusercontent.com/92590831/145730751-d93b178e-64de-412e-a61e-da81c86584fb.png)

![image](https://user-images.githubusercontent.com/92590831/145730830-afff9e84-c906-4502-b2c6-f61f7c008c27.png)

![image](https://user-images.githubusercontent.com/92590831/145730915-69f28ed5-bf23-4129-a750-384d5193d089.png)

![image](https://user-images.githubusercontent.com/92590831/145730930-1a41e861-c5d6-4505-a2f4-00712a24f597.png)




 ![image](https://user-images.githubusercontent.com/92590831/145730040-d5c04511-82cb-4789-bcb7-6f3f1441ffe0.png)

![image](https://user-images.githubusercontent.com/92590831/145730197-df8626ca-2a95-4e59-bbb3-f3a3966809a2.png)

![image](https://user-images.githubusercontent.com/92590831/145730273-66cac6fc-24b3-43b1-a389-5e57c715e3e4.png)

![image](https://user-images.githubusercontent.com/92590831/145730308-c51fe972-c618-4d47-ad4a-c1763d03afb1.png)
