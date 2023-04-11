University: ITMO University

Faculty: FICT

Course: Network programming

Year: 2022/2023

Group: K34212

Author: Ushakova Polina Aleksandrovna

Lab: Lab3

Date of create: 04.04.2023

Date of finished: 11.04.2023


# Построение сети ip-телефонии между удаленными маршрутизаторами

## Часть 1
1. Собрана схема сети

> Чтобы соединить два роутера между собой с помощью Serial DTE, в роутеры были добавлены модули WIC-2T.

![image](https://user-images.githubusercontent.com/90505004/228923812-4b83d725-abba-4c41-8fc5-67d6673d80db.png)

![image](https://user-images.githubusercontent.com/90505004/228924822-2108eacc-c2be-4c48-9ff1-15d9d30abd93.png)


2. Настроен интерфейс fa0/0 на маршрутизаторах Cisco 2811.

![image](https://user-images.githubusercontent.com/90505004/228925488-f4478c3f-9fa7-4e19-9232-1c803723ed8f.png)

3. Настроен интерфейс s0/3/0 на маршрутизаторах Cisco 2811.

![image](https://user-images.githubusercontent.com/90505004/228926368-76f7c284-4c7b-46bf-8514-1f0256aa8ea3.png)

4. Для автоматической настройки компьютеров и IP-телефонов в сети настроен DHCP сервер на маршрутизаторах.

![image](https://user-images.githubusercontent.com/90505004/228927574-76bae861-acd1-4cdb-8844-320d449a4198.png)

5. Выполнена настройка динамической маршрутизации на основе протокола RIP второй версии для передачи информации между маршрутизаторами в сети

![image](https://user-images.githubusercontent.com/90505004/228928775-444c4d1e-37f7-4f28-a7ca-a16b265a370a.png)

6. Выполнена настройка CallManager Express.

![image](https://user-images.githubusercontent.com/90505004/228929971-be6c85da-63db-404c-9309-d2286a911548.png)

7. Выполнено назначение диапазона портов.

![image](https://user-images.githubusercontent.com/90505004/228935608-b5ce8356-b9c5-48cf-b4bb-c0406d129bfa.png)

8. Выполнена настройка телефонии.

![image](https://user-images.githubusercontent.com/90505004/228936639-54d3e9ca-b2ae-4f9e-809e-94235f4fbaf3.png)

![image](https://user-images.githubusercontent.com/90505004/228937281-ec16cbc3-402d-43fe-bb03-18756f4780f4.png)

9. Настройка передачи звонков между удаленными сетями

![image](https://user-images.githubusercontent.com/90505004/228938322-28b8eead-6a5c-4d68-8bfa-c641aa63e975.png)


10. Выполнена проверка передачи данных между компьютерами и связь между телефонами.

![image](https://user-images.githubusercontent.com/90505004/228939023-6b4c79a4-aadb-4ac7-84e4-84d3cbb86fb5.png)

![photo_2023-03-30_22-14-11](https://user-images.githubusercontent.com/90505004/228941343-f57f639d-cd80-42d4-9019-d7471dd24aba.jpg)


Вывод: В результате проделанной работы изучено построение сети IP-телефонии междуудаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т

