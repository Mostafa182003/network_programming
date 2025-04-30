
University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Network programming](https://github.com/itmo-ict-faculty/introduction-in-routing)
Year: 2024/2025
Group: K3320
Author: Abdallah Mustafa Abdallah
Lab: Lab1
Date of create: 23.03.2025
Date of finished: - 


# Конфигурация сервера
Установим ансибл 


![](assets/server.png)

Из амнезии достанем .ovpn config


![](assets/ovpn.png)

# Конфигурация mikrotik
Установим время


![](assets/1.png)

Загрузим конфигурацию


![](assets/upload.png)

Импортируем


![](assets/import.png)

Подключение


![](assets/monitor.png)
![](assets/pring.png)

Добавим gateway для vpn и с помощью fetch на http://ifconfig.me/ip узнаем под каким ip нас "видит" 


![fetch](assets/addgateway.png)

188.126.76.169 - ip сервера на котором стоит vpn, значит все работает!
