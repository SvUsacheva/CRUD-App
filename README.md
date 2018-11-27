
Всем привет!

Во-первых, о новом задании. 
Оно будет на основе предыдущего, где вам нужно было создать базу и заполнить ее данными. 
Теперь мы хотим, чтобы вы научились  работать с этими данными (выполнять CRUD  операции) через Java приложение. 
Стандартная технология для работы с БД через java называется JDBC. В JDK есть стандартный JDBC , но с ним вы еще плотно поработаете на занятиях в УНЦ . 
 Мы же предлагаем использовать JDBC, входящий в состав Spring фреймворка - JdbcTemplate.
Итак, требования:
- приложение должно реализовывать следующие методы для обращения к вашей бд (вывод результата в консоль):
getEmployees()  /*returns list of  all employees*/
getProjectsByEmployee(int empId)  /*returns projects for specified employee*/
getCompanyByProjectName (String name)  /*returns company for specified  project*/
createEmployee(…)  /*creates new employee at DB*/
deleteEmployeeByName(String name)  /*deletes specified employee from DB*/;           
- сборку проекта и подтягивание зависомостей настроить с помощью Maven ;
- приложение реализует паттерн DAO;
- в приложении используется паттерн DI (Dependency Injection) – через конструктор или через сеттер (на ваш выбор); 

Подробности по ссылкам:
Про DI
http://www.tutorialspoint.com/spring/spring_dependency_injection.htm 
http://www.tutorialspoint.com/spring/constructor_based_dependency_injection.htm 
http://www.tutorialspoint.com/spring/setter_based_dependency_injection.htm 
http://stackoverflow.com/questions/3334578/what-is-dependency-injection
про Spring IoC и контексты
https://www.tutorialspoint.com/spring/spring_ioc_containers.htm 
про Spring JDBC  и DAO
http://www.tutorialspoint.com/spring/spring_jdbc_framework.htm 
http://docs.spring.io/spring/docs/current/spring-framework-reference/html/jdbc.html 
http://www.dokwork.ru/2014/02/daotalk.html 
http://javatutor.net/articles/j2ee-pattern-data-access-object 

Здесь всего очень много, не пугайтесь и ругайтесь, а пишите вопросы!
