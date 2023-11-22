# RFC
1. Executive summary
Компанія Company.Inc – стартап, який займається питаннями екології та збереження навколишнього середовища.
2. Project overview
Наразі компанія займається розробкою системи моніторингу екології, яка буде збирати інформацію про стан навколишнього середовища та матиме можливість передавати їх в контролюючі органи.

3. Ключові аспекти системи:
o	Integration: інтеграція з існуючими системами екологічного контролю
o	Flexibility: система повинна підтримувати велику кількість різноманітних датчиків для збору показників
o	Performance: система повинна підтримувати високу частоту оновлення даних з багатьох пристроїв та зберігати велику кількість даних для подальшого використання

3. Requirements
3.1.1 Інтерфейс
Система повинна мати зручний інтерфейс для перегляду даних про стан навколишнього середивища, та детальну інфографіку з основними показниками.
3.1.2 Підтримувані пристрої
Система повинна підтримувати велику кількість різних пристроїв для збору інформації:
	- датчики хімічного складу повітря
	- газоаналізатори
	- датчики хімічного складу грунту
	- датчики якості води
	- детектори нафтопродуктів
3.1.3 Public API
Система повинна реалізовувати публічний API для того щоб будь-хто бажаючий міг отримати дані в зручному форматі.
3.1.4 Експорт даних
Система повинна мати можливість експортувати дані в різних форматах, а також можливість генерації звітів на надсилання їх в контролюючі органи. 

# Список використаних технологій
Архітектурний дизайн: Модульний моноліт з  Event-driven підходом

Основна мова програмування:  C# with ASP.NET
Front-End частина: JavaScript with Angular 

API: RESTful 
Протокол: HTTPS
Документація: OpenAPI

База даних: Apache Cassandra (NoSQL)
Резервне копіювання бази даних: Apache Cassandra's nodetool

Middleware:
Потокова передача даних: Apache Kafka
Кешування: Redis (TTL)
Інтеграція з датчиками та сенсорами: Azure IoT Hub 
Протокол: MQTT
Оновлення в реальному часі: SignalR for ASP.NET 

Безпека:
Шифрування даних: TLS, AES
Керування ідентифікацією та доступом: Keycloak 
Протокол автентифікації та авторизації користувача: OAuth 2.0

CI/CD: Jenkins 

Інструменти моніторингу: Prometheus

# C4
![pLRTJkCy4BtFK_YE8b8Uu1Eg-DHTgIiLWMXv03UP9DvrxCXs2kpFk-_4SSmaflVBLNtcp9pv6JlSMyUDwrkPNR6jvDQo4YgXX1DQsQpmo9ON3JnmnMimx5V6y6_D39J2RgK0vTX_xFdZ5Eo5Tm9dH66Hi2N7m92wne1es_iV0OKpnZZq9riOSG9Z1xkmxkxh7D-mA_P_NHke-P0gWpVUTX9y](https://github.com/Alaska2222/C4-modular-monolith-with-EDA/assets/100542322/af3413d7-67f8-4ad4-a207-45206e93bc3d)
<img width="2158" alt="Page_2" src="https://github.com/Alaska2222/C4-modular-monolith-with-EDA/assets/100542322/cf3ff185-afab-4667-a847-6f122140e1b9">
<img width="1650" alt="Page_1" src="https://github.com/Alaska2222/C4-modular-monolith-with-EDA/assets/100542322/f7a4c6ff-21cd-4e10-aab9-48d172ef73b0">
<img width="1137" alt="Page" src="https://github.com/Alaska2222/C4-modular-monolith-with-EDA/assets/100542322/185eefc9-dfa6-4304-9be0-f207c94b1024">

Посилання на С4 модель:
-	Context, container, component: [C4.vsdx](https://lpnu-my.sharepoint.com/:u:/g/personal/mariia-korneliia_drozd_kn_2021_edu_lpnu_ua/EfEMFNelDAxGl4tlOGzPR84BRNdr1VgEq-ztgt5Hxkh5cg?rtime=yuUxPGPr20g)https://lpnu-my.sharepoint.com/:u:/g/personal/mariia-korneliia_drozd_kn_2021_edu_lpnu_ua/EfEMFNelDAxGl4tlOGzPR84BRNdr1VgEq-ztgt5Hxkh5cg?rtime=yuUxPGPr20g
-	Class: https://shorturl.a¬t/acsC7
