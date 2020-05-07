# AirlineSystemTaskForEpamCourse

**`Система Авиакомпания.`**  
Авиакомпания имеет список рейсов. Диспетчер формирует летную Бригаду (пилоты, штурман, радист, стюардессы) на Рейс.
Администратор управляет списком рейсов.

**`Task 1`**  
Разработать подсистему для работы с базой данных предложенной предметной области:  
1 Разработать схему базы данных в соответствии с предметной областью вашего варианта.  
2 Создать sql-скрипты создания БД, пользователя БД, создание таблиц, заполнение таблиц, удаление данных, удаление таблиц, удаление БД, обновление данных, запросы на выборку данных.  
3 Информацию о предметной области хранить в БД, для доступа использовать API JDBC с использованием пула соединений, разработанного самостоятельно. В качестве СУБД используется MySQL.  
4 На основе сущностей предметной области создать классы их описывающие.  
5 Классы и методы должны иметь отражающую их функциональность названия и должны быть грамотно структурированы по пакетам.  
6 Оформление кода должно соответствовать Java Code Convention.  
7 Приложение должно поддерживать работу с кириллицей (быть многоязычной), в том числе и при хранении информации в БД.  
8 Выполнить журналирование событий, то есть информацию о возникающих исключениях и событиях в системе обрабатывать с помощью Log4j 2.  
9 Код должен содержать комментарии.

**`Task 2`**  
Построить веб-систему (для предметной области в соответствии с вариантом task 1), поддерживающую заданную функциональность:  
1 Интерфейс приложения должен поддерживать работу с кириллицей (быть многоязычной).  
2 Архитектура приложения должна соответствовать шаблону Model-View-Controller.  
3 При реализации алгоритмов бизнес-логики использовать шаблоны GoF: Factory Method, Command, Builder, Strategy, State, Observer etc.  
4 Используя сервлеты и JSP, реализовать функциональности, предложенные в постановке конкретной задачи.  
5 В страницах JSP применять библиотеку JSTL и разработать собственные теги.  
6 При разработке бизнес логики использовать сессии и фильтры.  
7 Код должен содержать комментарии.

