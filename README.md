# Домашнее задание к занятию "Что такое DevOps. СI/СD" - Качьянов Вадим


### Задание 1

Сделан Freestyle Job, который запускает тесты, собирает docker-образ и пушит его в Nexus.

1) Jenkins
![jenkins](img/jenk1.1.png)
2) Настройки проекта
![config](img/jenk1.2.png)
3) Результат сборки
![build](img/jenk1.3.png)



### Задание 2

Freestyle Job переделан в Declarative Pipeline.

1) Pipeline
![pipeline](img/jenk2.1.png)
2) Результат сборки
![build](img/jenk2.2.png)



### Задание 3

В Nexus создан raw-hosted репозиторий. Pipeline собирает бинарник go и загружает его в Nexus.

1) Nexus
![nexus](img/nexus3.1.png)
2) Создание репозитория
![repo](img/nexus3.2.png)
3) Pipeline
![pipeline](img/jenk3.3.png)
4) Результат сборки
![build](img/jenk3.4.png)
5) Бинарник в Nexus
![binary](img/nexus3.4.png)



### Задание 4*

Версия задаётся через переменную VERSION = 1.0.$BUILD_NUMBER, каждая сборка загружается в Nexus в свою папку.

1) Pipeline
![pipeline](img/jenk4.1.png)
2) Версия в Nexus
![version](img/nexus4.1.png)
