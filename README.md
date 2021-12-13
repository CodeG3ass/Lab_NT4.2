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

![image](https://user-images.githubusercontent.com/92590831/145878685-2c96a638-42a6-420d-93da-66a45cd79d04.png)

![image](https://user-images.githubusercontent.com/92590831/145878949-da54a3a5-d76f-493d-ae09-229c8cd2cf61.png)

![image](https://user-images.githubusercontent.com/92590831/145879485-68677d98-e012-42ac-bd7c-4e0d7de74afd.png)

![image](https://user-images.githubusercontent.com/92590831/145879638-2e18ee2a-8446-4d29-809e-7e0abb891aca.png)

![image](https://user-images.githubusercontent.com/92590831/145879810-c0e96cc0-e054-48a0-b413-33633d3476bb.png)

![image](https://user-images.githubusercontent.com/92590831/145879972-ef4e1cea-a17b-4bc8-b68e-f052a0c89037.png)

![image](https://user-images.githubusercontent.com/92590831/145880006-dbd12375-8b35-42d7-bab1-1a06f24440d9.png)

![image](https://user-images.githubusercontent.com/92590831/145880046-8bfabae2-5094-4a3f-8b66-510c12bd5f11.png)

Создать самоподписанный сертификат для сайтов A1.com, B1.com, C1.com 

![image](https://user-images.githubusercontent.com/92590831/145884298-d2ffb916-3961-4254-9bcd-38d8df92133a.png)

![image](https://user-images.githubusercontent.com/92590831/145888165-3643bbc4-9240-4feb-8eb8-b571dfe71d06.png)

![image](https://user-images.githubusercontent.com/92590831/145888179-dbcc00c3-1f25-4267-9abe-cc180669b1b0.png)


Организовать работу Apache с по протоколу HTTPS (SSL) 

Перенаправление HTTP в HTTPS для Apache 

![image](https://user-images.githubusercontent.com/92590831/145881816-ceebfbea-07a8-4305-bd0e-d38be0a2b51e.png)

![image](https://user-images.githubusercontent.com/92590831/145883839-f20fe15f-3892-43ef-9ec4-b1f169de2afc.png)

![image](https://user-images.githubusercontent.com/92590831/145883856-9291c48d-4ac2-461c-89c0-e7b39502e4b5.png)

 

Дополнительные задания: 


Просмотреть содержимое сертификата 

Просмотреть содержимое сертификата в режиме обычного текста 

Проверить действительно ли сертификат подписан нужным CA 

Перевести Nginx на работу  с использование самоподписанного сертификата SSL 

Настроить отправку файлов проекта и конфигурации на GitHub 
