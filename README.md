# SpringBoot

- SpringBoot MySQL 연동  
src/main/resources/application.properties에 아래 내용 추가
```
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/(DB이름)?serverTimezone=UTC&characterEncoding=UTF-8
spring.datasource.username=root	# 계정명
spring.datasource.password=0000	# 비번
```
