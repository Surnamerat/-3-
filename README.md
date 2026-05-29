# autosalon-service-app

Курсовой проект: веб-приложение для автоматизации обработки клиентских обращений на сервисное обслуживание в автосалоне.

## Технологии

- Java 17+
- Spring Boot 3.3.5
- Spring Web
- Spring Security
- Spring Data JPA
- Thymeleaf
- H2 Database
- Maven

## Запуск

1. Открыть проект в IntelliJ IDEA как Maven Project.
2. Убедиться, что Project SDK = JDK 17 или выше.
3. Убедиться, что Language level = 17.
4. Запустить `src/main/java/ru/kurs/autosalon/AutosalonServiceApplication.java`.
5. Открыть `http://localhost:8080`.

## Логины

- admin / admin123
- manager / manager123
- master / master123

## Важно

Если IntelliJ IDEA пишет `JVM target 5`, нужно открыть:

File → Project Structure → Project → Language level: 17
File → Project Structure → Modules → Sources → Language level: 17
File → Settings → Build, Execution, Deployment → Compiler → Java Compiler → Target bytecode version: 17

После этого Maven → Reload Project и Build → Rebuild Project.
