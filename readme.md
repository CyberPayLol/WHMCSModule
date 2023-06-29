# WHMCS Module
> Модуль, разработанный для движка WHMCS 8+, который позволяет создавать платежи и проверять их статус (осуществлять выдачу)

---
#### Инструкция
##### 1. Установка аддона
- 1.1. Переместите папку "modules" в корень вашего сайта (/)
- 1.2. Перейдите в вкладку Настройки -> Apps & Integrations -> Search, введите в поле поиска "CyberPay" и нажмите "Activate" (/admin/apps/search)
![image](https://github.com/CyberPayLol/WHMCSModule/assets/102430482/9a80fb7a-a949-42fc-a735-c5030baa3704)
##### 2. Настройка аддона
- 2.1. После активации модуля WHMCS перекинет на страницу его настройки, если этого не произошло, перейдите в вкладку Настройки -> Платежные шлюзы (/admin/configgateways.php)
![image](https://github.com/CyberPayLol/WHMCSModule/assets/102430482/0720b646-14dd-4f8d-9807-aa1b6fa21f9b)
- 2.2. Введите любое отображаемое название, в поле "UUID магазина" введите UUID, который можно получить, нажав на "?" в панели магазина. Также можно выбрать, с кого взимать комиссию и выбрать метод оплаты
![image](https://github.com/CyberPayLol/XenForoModule/assets/102430482/4ed50e92-2c76-401f-a6d8-b541b440e0fc)
- 2.3. Готово. Теперь клиент при оплате сможет выбрать, каким модулем оплачивать, в том числе и CyberPay
![image](https://github.com/CyberPayLol/WHMCSModule/assets/102430482/3a2eed70-6c94-48aa-ae34-f7c04c67b0c2)

---

## Лицензия

Copyright © 2023 [CyberPay](https://github.com/CyberPayLol)

Проект распространяется под лицензией [MIT](LICENSE)
