# EmailApp

<dependency>
      <groupId>org.springdoc</groupId>
      <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
      <version>2.0.2</version>
    </dependency>


Add in Properties file->

spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=your_email_id
spring.mail.password=your_password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true