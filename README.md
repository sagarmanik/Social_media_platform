# Social_media_platform By Sagar Manik
Table of Contents
Installation
Frontend Setup
Backend Setup
Scripts
Configuration
Running the Application


#FRONTEND
git clone https://github.com/sagarmanik/Social_media_platform
cd frontend

npm init -y
npm install react-redux redux react-router-dom axios
npm start


#BACKEND
spring.datasource.url=jdbc:mysql://localhost:3306/huddle_up
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true

mvn clean install
mvn spring-boot:run




FIRST RUN THE BACKEND WITH SPRINBOOT ON http://localhost:8080
AFTER THAT RUN THE BACKEND WITH REACT ON PORT http://localhost:3000



FOR MORE : EMAIL;sagarmanik526@gmail.com

![Screenshot 2024-11-11 154127](https://github.com/user-attachments/assets/c4717649-94ec-461e-a9ea-adc3bbf435f0)

![Screenshot 2024-11-11 154112](https://github.com/user-attachments/assets/e0d8e6ad-d7a7-4a83-b903-5e0491478c52)


