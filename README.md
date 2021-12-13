# Lab_NT4.2
Балансировка нагрузки и сертификаты SSL 
Балансировка нагрузки и сертификаты SSL 

Цель работы 

Получить навыки продвинутой настройки сложного взаимодействия сетевых служб и сервисов в ОС Linux. 

Задания для выполнения 

Работа производится на виртуальной машине с установленным в ходе предыдущих работ сервером Apache и настроенными виртуальными хостами. 

![image](https://user-images.githubusercontent.com/92590831/145872071-17ab48bb-d7ad-45e2-959d-b998cf5b027d.png)

Установить в виртуальной машине сервер Nginx. 

Настроить сервера Apache и Nginx так, чтобы 8080 порт Apache получал запросы 80 порта Nginx. 
![image](https://user-images.githubusercontent.com/92590831/145872348-8a585ea2-8d07-48a1-92c7-a49795bebf4c.png)

![image](https://user-images.githubusercontent.com/92590831/145871288-740ee625-09c6-4fce-b563-82106359e935.png)

Проверяем A1.com, Nginx accessA1.log должен пополняться при обращении к сайту. 

![image](https://user-images.githubusercontent.com/92590831/145871750-6e8c0eb3-0e52-4c6a-a32f-3bbe915c0656.png)

![image](https://user-images.githubusercontent.com/92590831/145872481-47804bca-22a7-42c1-a665-a469e21ff58a.png)

![image](https://user-images.githubusercontent.com/92590831/145872429-a4e20794-7376-4945-bf1e-87fa7ddbdc54.png)

![image](https://user-images.githubusercontent.com/92590831/145872563-34df7ddd-0ba4-4147-bc8d-628ee7e9bb49.png)

Проверяем B1.com, Nginx accessB1.log должен пополняться при обращении к сайту. 

![image](https://user-images.githubusercontent.com/92590831/145871788-c3ac8ff8-b703-406e-9980-7b76ca738d32.png)

![image](https://user-images.githubusercontent.com/92590831/145872655-17ae4b9a-48f9-443d-9c14-189e329eed41.png)

![image](https://user-images.githubusercontent.com/92590831/145872602-ce88ce53-a06c-41c2-80d7-6730430b6bc2.png)

![image](https://user-images.githubusercontent.com/92590831/145872925-9eb7264b-0ab0-4e3a-b7c0-473db687dc8b.png)

Проверяем C1.com, Nginx accessC1.log должен пополняться при обращении к сайту. 

![image](https://user-images.githubusercontent.com/92590831/145871812-7b2427a6-b4f1-44af-a8ae-3bac83e705d4.png)

![image](https://user-images.githubusercontent.com/92590831/145872995-47085198-91d4-483f-ac19-4a12b13919be.png)

![image](https://user-images.githubusercontent.com/92590831/145873020-984b879d-3313-459a-b6d2-f68453a0b8dd.png)

![image](https://user-images.githubusercontent.com/92590831/145873055-a9241ea3-8122-4a72-8cd1-8cb6e59d09aa.png)

Log файлы должны быть разные для каждого сайта 


Делаем, чтобы Nginx всё, кроме jpg и png файлов передавал Apache. 

![image](https://user-images.githubusercontent.com/92590831/145878450-2acf3a12-5606-4e40-952f-ab489424c014.png)


![image](https://user-images.githubusercontent.com/92590831/145878078-f4c43034-d765-4b95-959c-bb867a2cba13.png)

![image](https://user-images.githubusercontent.com/92590831/145878505-e351f25f-187e-4a14-9382-e4b74eeae15e.png)

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


![image](https://user-images.githubusercontent.com/92590831/145870008-2a98ee78-0d7c-440c-824e-f4d8c6440004.png)

![image](https://user-images.githubusercontent.com/92590831/145871000-cd0d6abf-7cfe-497f-971f-332b02f3b825.png)

 ![image](https://user-images.githubusercontent.com/92590831/145730040-d5c04511-82cb-4789-bcb7-6f3f1441ffe0.png)

![image](https://user-images.githubusercontent.com/92590831/145730197-df8626ca-2a95-4e59-bbb3-f3a3966809a2.png)

![image](https://user-images.githubusercontent.com/92590831/145730273-66cac6fc-24b3-43b1-a389-5e57c715e3e4.png)

![image](https://user-images.githubusercontent.com/92590831/145730308-c51fe972-c618-4d47-ad4a-c1763d03afb1.png)
