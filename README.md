# Лабораторная работа по дисциплине "Архитектура корпоративных систем"
В в ходе лабораторной работы было изучены такие понятия как:
- Клиент серверное приложение;
- HTTP request/response;
- Apachhe Tomcat;
- Сервлет и его жизненный цикл;
- Redirect и Forward;
- Cookie;
- JDBC и SQL (SQL инъекция);
- Spring framework;
- IoC, DI;
- CRUD, REST, DAO(Data Access Object);


Web приложение реализованно на следующих версиях технологий и инструментов:
- JDK 16.0.2
- Spring Boot 2.5.5
- Tomcat 9.0.52
- PostgreSQL 13.3
- Intellij IDEA Ultimate 2021.2.1

Диаграммы сущностей:
![image](https://user-images.githubusercontent.com/83270014/222102539-506ef5bc-4830-44b3-820f-7961846fab97.png)

SQL scripts:
- drop_create_schema - drops the tables if they exist and then creates them
- insert_data - inserts data to the created tables
- delete_data - deletes all data from the tables

Работа с форматом JSON:

- POST    localhost:8080/ESAPracticalWork3_war/courses/create — создать новый курс
- GET     localhost:8080/ESAPracticalWork3_war/courses — получить все курсы
- GET     localhost:8080/ESAPracticalWork3_war/courses/:id - получить один курс по id
- PATCH   localhost:8080/ESAPracticalWork3_war/courses/:id/update - обновить один курс по id
- DELETE  localhost:8080/ESAPracticalWork3_war/courses/:id/delete - удалить один курс по id
- POST    localhost:8080/ESAPracticalWork3_war/groups/create — создать новую группу
- GET     localhost:8080/ESAPracticalWork3_war/groups — получить все группы
- GET     localhost:8080/ESAPracticalWork3_war/groups/:id — получить одну группу по id
- PATCH   localhost:8080/ESAPracticalWork3_war/groups/:id/update - обновить одну группу по id
- DELETE  localhost:8080/ESAPracticalWork3_war/groups/:id/delete - удалить одну группу по id
- GET     localhost:8080/ESAPracticalWork3_war/groups/:id/courses — получить все курсы группы по id
- GET     localhost:8080/ESAPracticalWork3_war/groups/:id/students — получить всех учеников группы по id
- POST    localhost:8080/ESAPracticalWork3_war/students/create — создать нового ученика
- GET     localhost:8080/ESAPracticalWork3_war/students — получить всех учеников
- GET     localhost:8080/ESAPracticalWork3_war/students/:id - получить одного студента по id
- PATCH   localhost:8080/ESAPracticalWork3_war/students/:id/update - обновить одного ученика по идентификатору
- DELETE  localhost:8080/ESAPracticalWork3_war/students/:id/delete - удалить одного ученика по id


Show groups
![image](https://user-images.githubusercontent.com/83270014/222093687-34fcd383-1cfe-4fcd-b5c3-fd439e42a4f5.png)

Show courses
![image](https://user-images.githubusercontent.com/83270014/222093909-740986d9-90e5-4d17-a981-952ff4e87019.png)

Show students
![image](https://user-images.githubusercontent.com/83270014/222094390-a8479f54-c5d4-439f-9c6f-b8dd8caee1ea.png)

Create group
![image](https://user-images.githubusercontent.com/83270014/222094484-75d91344-d2a0-4317-bfba-6acc735470b1.png)

Create course
![image](https://user-images.githubusercontent.com/83270014/222094579-8c043f40-c0ac-4389-9ac7-a0a8693f7669.png)

Create students 
![image](https://user-images.githubusercontent.com/83270014/222094693-5dcee57d-f2fa-42fd-8f98-7da0fbd41188.png)

Update groups
![image](https://user-images.githubusercontent.com/83270014/222094853-83d16499-bd50-467b-9529-21853aa5256c.png)

Update course
![image](https://user-images.githubusercontent.com/83270014/222095671-342957a2-d899-4866-a086-107fd9924e13.png)

Update student
![image](https://user-images.githubusercontent.com/83270014/222095914-5c6572dc-0b5f-4e0b-9aa6-36d8b2d26d45.png)

