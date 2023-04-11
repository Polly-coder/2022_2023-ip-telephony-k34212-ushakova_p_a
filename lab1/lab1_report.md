University: ITMO University

Faculty: FICT

Course: Network programming

Year: 2022/2023

Group: K34212

Author: Ushakova Polina Aleksandrovna

Lab: Lab1

Date of create: 04.04.2023

Date of finished: 11.04.2023


# Базовая настройка ip-телефонов в среде Сisco packet tracer

## Часть 1

+ Собрана схема связи в Cisco Pacet Tracer.

![image](https://user-images.githubusercontent.com/90505004/222944972-0a5e41d3-fc7f-404e-b4cf-bf57f97f8724.png)

+ Каждому компьютеру задан свой ip адрес.

![image](https://user-images.githubusercontent.com/90505004/222945134-9f3b1975-71f7-44f5-ad35-b3991b5661a3.png)

+ С помощью команды пинг была проверена свзяь между компьютерами, все работает успешно.

![image](https://user-images.githubusercontent.com/90505004/222945243-d17d1532-ab6f-4bd6-aa64-f43f38727016.png)
![image](https://user-images.githubusercontent.com/90505004/222945298-db34e58e-d2e4-44c0-9d12-0ce94cf0a2ee.png)
![image](https://user-images.githubusercontent.com/90505004/222945337-62248536-54d4-425f-af31-3fe1f5774d58.png)


## Часть 2

+ Собрана схема связи из роутера, свитча, 2 ip телефонов.

![image](https://user-images.githubusercontent.com/90505004/222945074-cf1cc151-fa44-41f9-9625-c91632138e2a.png)

+ Изменено имя маршрутизатора CMERouter

### Настройка интерфейса роутера

+ Задана адресация для интерфейса роутера, отвечающего за подсеть

![image](https://user-images.githubusercontent.com/90505004/222945466-be958cac-6d21-47a6-b73e-779fff0ec31c.png)

+ Поднят DHCP сервер на маршрутизаторе для IP – телефонов

![image](https://user-images.githubusercontent.com/90505004/222945852-74ca78a3-fcb6-495d-98d6-e5c9115c8937.png)

+  Поднята опция, которая автоматически подтягивает прошивки для телефонов

![image](https://user-images.githubusercontent.com/90505004/222945940-9ee3ed1c-93d0-4be4-984c-dc9d7bc5a9fd.png)

+ Настроен VoIP со следующими параметрами

> max-dn - максимально – возможное количество поддерживаемых DN (Directory Numbers) или же максимальное количество телефонных аппаратов

> max-ephones - максимальное количество телефонных аппаратов

> ip source-address - откуда роутер будет принимать звонки (запросы)

> auto assign - присвоение линий в автоматическом режиме

![image](https://user-images.githubusercontent.com/90505004/222946038-c271479b-be41-4637-9aae-b4d4addf6e34.png)

+ Настроен свитч. Включена поддержка VoIP на интерфейсах (голосовой VLAN)

![image](https://user-images.githubusercontent.com/90505004/222946219-0652699b-65bf-4d24-986b-33bb5255d228.png)

+ Присвоены телефонные номера аппаратам

![image](https://user-images.githubusercontent.com/90505004/222946314-a5151e74-d594-4d30-9862-9441c3691527.png)

+ Каждому телефону подключено питание

![image](https://user-images.githubusercontent.com/90505004/222946423-b7cc36c5-ceb2-46ca-ae9a-c89bc82c9b74.png)

+ Произведены звонки с телефонов друг другу. Все работает успешно

![image](https://user-images.githubusercontent.com/90505004/222946387-5b86ba3a-a1b4-43a6-be93-073dc0b40e45.png)

## Вывод

В результате проделанной работы получены навыки работы с Cisco Packet Tracer, смоделирована VoIP-сеть.
