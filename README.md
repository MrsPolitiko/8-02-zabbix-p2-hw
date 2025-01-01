# Домашнее задание к занятию "Система мониторинга Zabbix. Часть 2" - `Политико Ксения`


---

### Задание 1
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.
![Решение задания 1](./img/task1.png)

---

### Задание 2
Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.
![Решение задания 2](./img/task2.png)
---

### Задание 3
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.
![Решение задания 3](./img/task3.png)


---

### Задание 4
Создайте свой кастомный дашборд.
![Решение задания 4](./img/task4.png)


---

### Задание 5

Создайте карту и расположите на ней два своих хоста.


---

### Задание 6

Создайте UserParameter на bash и прикрепите его к созданному вами ранее шаблону. Он должен вызывать скрипт, который:

* при получении 1 будет возвращать ваши ФИО,
* при получении 2 будет возвращать текущую дату.

---


### Задание 7

---

### Задание 8
Настройте автообнаружение и прикрепление к хостам созданного вами ранее шаблона.


---

### Задание 9
Доработайте скрипты Vagrant для 2-х агентов, чтобы они были готовы к автообнаружению сервером, а также имели на борту разработанные вами ранее параметры пользователей.
