# final_NetTech

Для запуска необходим Cisco Packet Tracer 8.2.0, пароли сетевых устройств - 1111

Организована локальная сеть в 4 филиалах (в каждом отделе по 23 сотрудника). Коммутаторы одного отдела соединяются последовательно, используя агрегирование (lacp).На каждом коммутаторе отдела подключается по 3 ПК для сотрудников (все 23 ПК подключать не нужно, но коммутаторы настраиваются для их подключения). Для каждого отдела настраивается DHCP. Используется выделенный dhcp-сервер
Филиалы выделены в отдельные VLAN, каждое устройство защищается паролем и имеет адрес управления в единой сети управления.
На ПК настроен port-security - запоминается mac-адрес, при подключении к порту устройства с другим адресом порт отключается.

![image](https://github.com/user-attachments/assets/997c6706-a999-428a-9cc1-8c6fff2e137b)
