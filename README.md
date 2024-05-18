# Домашнее задание к занятию Disaster-recovery-Keepalived - Николаев Еыгений
### Задание 1
- Дана [схема](1/hsrp_advanced.pkt) для Cisco Packet Tracer, рассматриваемая в лекции.
- На данной схеме уже настроено отслеживание интерфейсов маршрутизаторов Gi0/1 (для нулевой группы)
- Необходимо аналогично настроить отслеживание состояния интерфейсов Gi0/0 (для первой группы).
- Для проверки корректности настройки, разорвите один из кабелей между одним из маршрутизаторов и Switch0 и запустите ping между PC0 и Server0.
- На проверку отправьте получившуюся схему в формате pkt и скриншот, где виден процесс настройки маршрутизатора.

------
### Выполнения задания 1

![Image alt](img/config.jpg)

![Image alt](img/ping1.jpg)

![Image alt](https://github.com/Byzgaev-I/Keepalived/blob/main/Keepalive%201.png)

![Image alt](https://github.com/Byzgaev-I/Keepalived/blob/main/Keepalive%201.png)

[Схема решения](https://github.com/Byzgaev-I/Keepalived/blob/main/1-hsrp_advanced_Netology.pkt)
