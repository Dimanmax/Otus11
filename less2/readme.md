### Создал топологию как в задании

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/%D1%82%D0%BE%D0%BF%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%8F.jpg)](https://github.com/Dimanmax/Otus11/blob/main/less2/%D1%82%D0%BE%D0%BF%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%8F.jpg)
Выполнил первичную настройку :


[![](https://github.com/Dimanmax/Otus11/blob/main/less2/1.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/1.png)

Далее также продолжаем:

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/2.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/2.png)

Далее ограничим доступ к vty линиям с 0 по 5

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/3.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/3.png)

Сохраняем изменения

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/5.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/5.png)

Ребутаемся и проверяем изменения

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/6.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/6.png)

Как видим, пароль на вход уже установлен, также стоит банер

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/7.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/7.png)

Настроим SVI На коммутаторе:

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/8.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/8.png)

Настроил IP на Компьютере PC-A

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/10.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/10.png)

Пинг с ПК до коммутатора и обратно есть

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/11.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/11.png)
[![](https://github.com/Dimanmax/Otus11/blob/main/less2/12.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/12.png)

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/12.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/12.png)

Проверим подключение по телнет с ПК

[![](https://github.com/Dimanmax/Otus11/blob/main/less2/13.png)](https://github.com/Dimanmax/Otus11/blob/main/less2/13.png)

# Ответы на вопросы:

*1) Почему нужно использовать консольное подключение для первоначальной настройки коммутатора?*

Необходима первичная настройка для предоставления дальнешего доступа.

*2) Почему нельзя подключиться к коммутатору через Telnet или SSH?* 

При дефолтной конфигурации коммутатора - отсутствует доступ по обоим протоколам, необходимо предаварительно настроить.

*3) Сколько интерфейсов FastEthernet имеется на коммутаторе 2960?*

24 - FastEthernet

*4) Сколько интерфейсов FastEthernet имеется на коммутаторе 2960?*

2 - GigabitEthernet

*5) Каков диапазон значений, отображаемых в vty-линиях?*

0-15

*6) Под управлением какой версии ОС Cisco IOS работает коммутатор?*

 SW Version 15.0(2)SE4

*7) Как называется файл образа системы?*

   SW Image - C2960-LANBASEK9-M

*8) Интерфейс включен или выключен?*

  по дефолту выкл, надо включать самому.
  
*9) Что нужно сделать, чтобы включить интерфейс?*

 через команду no sh находясь на самом интерфейсе.
 
*10) Какой MAC-адрес у интерфейса?*

 0001.c9ba.9106
 
*11) Какие настройки скорости и дуплекса заданы в интерфейсе?*

Full-duplex, 100Mb/s

*12) Какое имя присвоено образу Cisco IOS?*

2960-lanbasek9-mz.150-2.SE4.bin
