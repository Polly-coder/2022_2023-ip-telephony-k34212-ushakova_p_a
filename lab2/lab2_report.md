University: ITMO University

Faculty: FICT

Course: Network programming

Year: 2022/2023

Group: K34212

Author: Ushakova Polina Aleksandrovna

Lab: Lab2

Date of create: 04.04.2023

Date of finished: 11.04.2023


# Конфигурация voip в среде Сisco packet tracer

## Часть 1
1. В конфигурационном режиме изменено название маршрутизатора на CMERouter.

![image](https://user-images.githubusercontent.com/90505004/226175214-18b15f3e-2016-4da7-a955-bd453844a7a8.png)

2.Отключен синтаксис ввода слов от DNS серверов, используя команду `no ip domain-lookup `.

![image](https://user-images.githubusercontent.com/90505004/226175494-3730215a-adfb-4e7d-9444-d70a02218580.png)

3. Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.

![image](https://user-images.githubusercontent.com/90505004/226175698-c88c7772-0f31-41ee-bc10-69411b640fa1.png)

4. Настроен интерфейс fa0/0 на маршрутизаторе CMERouter, задан ip адрес, маска сети, статус порта переведен в активный.

![image](https://user-images.githubusercontent.com/90505004/226175835-603e28e7-db15-4d19-9844-2e2ee0a1bce6.png)

5. Настрен DHCP сервера для передачи голоса и данных на маршрутизаторе

![image](https://user-images.githubusercontent.com/90505004/226176069-d7f71fa4-5ad2-42af-8657-52f8f1e4e262.png)

6. Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе.

![image](https://user-images.githubusercontent.com/90505004/226176942-7807dd96-25b3-4ffe-b35d-36180969277a.png)

7. Создать VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключить IP телефоны. Настроены IP-телефоны и соединены с коммутатором.

![image](https://user-images.githubusercontent.com/90505004/226177947-9b9d8509-6485-4c43-9761-30e56ca805ae.png)
![image](https://user-images.githubusercontent.com/90505004/226178101-d619cbf9-e5b1-4361-b0e9-3fca5aa33eae.png)

8. Проверены звонки между телефонами.

![image](https://user-images.githubusercontent.com/90505004/226178324-726ed0a8-3587-47ca-a83c-ef68956cdac8.png)

9. В результате собрана сеть.

![image](https://user-images.githubusercontent.com/90505004/226179049-c886639f-47cd-4e26-865b-e80ad5c6219d.png)


## Часть 2

1. Собрана схема.

![image](https://user-images.githubusercontent.com/90505004/226179282-4767b7a6-09f7-4282-be5c-ffa577f94c08.png)

2. Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.

![image](https://user-images.githubusercontent.com/90505004/226180598-a861fe06-0487-44c3-844e-928c16b064b0.png)

3. Настроены интерфейсы коммутатора, связанные с телефонами: интерфейсы переведены в режим доступа со стандартной и голосовой виртуальной сетью.

![image](https://user-images.githubusercontent.com/90505004/226181099-ea391785-3347-4a85-92d6-d8c66b6fe5f4.png)
![image](https://user-images.githubusercontent.com/90505004/226181105-5e3bea56-265d-40ad-a393-0ae4ff7b95df.png)

4. Задан маршрут по умолчанию командой ip default-gateway. Настроен порт как канал типа trunk.

![image](https://user-images.githubusercontent.com/90505004/226181375-5933b4d8-bf11-49e6-bd85-6f94662e53df.png)

5. Созданы логические подинтерфейсы под каждый VLAN.

![image](https://user-images.githubusercontent.com/90505004/226182068-05576c57-7fe4-414f-b502-cd582d19173b.png)

6. Исключены из пула адрес интерфейса маршрутизатора и DNS-сервера.  Настраены DHCP сервера для передачи голоса и данных на
маршрутизаторе.

![image](https://user-images.githubusercontent.com/90505004/226182442-5720152e-573f-4e07-8260-c7c37ffb022a.png)

7. Присвоены номера для всех IP-телефонов в сети

![image](https://user-images.githubusercontent.com/90505004/226182764-04db6984-4bbf-481f-88f3-a03962fac48b.png)

8. Проверка доступности устройств.

![image](https://user-images.githubusercontent.com/90505004/226183013-ea53bf8d-37b5-4dbf-9e2b-e54d47d11831.png)

9. Проверка доступности с компьютера.

![skrin](https://user-images.githubusercontent.com/90505004/226315752-63c66a8e-af59-40a1-b409-51f5bb0e29dd.png)


10. Проверка звонков между телефонами.

![яя](https://user-images.githubusercontent.com/90505004/226184472-4a33b712-6e1c-4287-8b40-aa76c394f031.jpg)

Вывод: В результате проделанной работы изучена схема настройки IP-телефонии с помощью CallManager Express.
